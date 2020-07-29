

inital bash test

create a bash script
```
 #!/bin/bash

 printf "\n selected option is working. \n\n"
 mkdir what

 # this works
```

#### add a bash script to run tests
package.json
```
    "scripts": {
      "test": "echo \"Error: no test specified\" && exit 1",
      "insta":"bash ./test"
    },
```
> eventually i will be adding the string to install

```
  npm init --scope=@sunzao

    creates:

  "name": "@sunzao/npm-insta-pkgs",
```
i can add the scope name to the package name myself and still make packages automatically
```
  npm init -y
```
