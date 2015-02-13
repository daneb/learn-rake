## Rake Sample

### Basic Commands

#### #rake -T
List all the tasks that have been defined

#### #rake -T -A
List all the tasks included those without a description

#### #rake db:create
Access DB namespace to execute task "create"

### Structure
* Rakefile - contains all the tasks
* rakelibs - directory that contains all the dependencies (breaking up code into modules)

### Last Words
Rakefiles are basically just ruby files, so thats the language that defines their syntax

#### Dane Balia 2015/02/13
