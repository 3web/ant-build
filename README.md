# ant-build

## Composer install
Install the composer dependencies.
```
composer:install
```
## Composer update
Update the composer dependencies.
```
composer:update
```

## Build Workflow
```
validate
|compile
|-test
|--package
|---integration-test
|----verify
```

## Clean
Clean the target direcory.
```
clean
```

## phpdoc
Create the php doc.
```
phpdoc
```

## Tagging
Tag the source code. <strong>JDK 8 is required!</strong>
```
tagging
```

## Ent to end Test
Run enduser test.
```
e2e-test
```

## Use
To use, create a main xml:

Copy the build.xml.dist as build.xml in project main.

## for a clean arcive
Add the following in the composer config. file.
```
 "archive": {
   "exclude": [".DS_Store", ".localized", "thumbs.db", "desktop.ini",
     "$Recycle.bin", ".git", ".svn", "nbproject/", "*.phar",
     "target/*", "*.properties", "build.xml"]
 }  
```
