# review-cdk-nextjs-typescript

## Cdk
 - app --> multiple (stack) --> multiple (construct)
 - l1: cloudformation resource --> configure resource settings
 - l2: higher-level of l1 :
   - sensible defaults
   - security best practices
   - helper methods
 - l3: pattern: limited control of underlying resources (pre-mode architecture)
 - construct hub
 - common commands:
   - cdk init --language typescript
   - cdk bootstrap
   - cdk synth --> generate the cloudformation template on the fly
   - cdk deploy
   - cdk destroy
   - cdk watch
   - cdk list

## typescript
 - never keyword: used it at compile time instead of run time
   - a function that always throws an error
   - a function that has an infinite loop
   - a variable that can never have a value
 - array:
   - const numbers: number[] = [...]
   - const names: Array<string> = [...] (old)
 - object
 - type aliases
   - type <type-name> = <type>
 - optional property --> undefined
 - readonly property --> cannot be changed after initialization
 - intersection types --> & : combine multiple types
 - unions  --> | : select one of several possible types
 - literal types --> let color: 1 | 2 | 3, can only be assigned one of the possible values
 - tuples: fixed number of items, each item can have different types
   - let mytuple: [string, number] = ['hello',323]
   - restructuring: let [first, second] = mytuple
 - enum: a set of named constants
   - enum <enum name> {22,34,6,8} or {snu='fawe',awef='age'}
 - OOP:
   - access modifier: public/private/protected
   - in javascript/typescript, getter/settting:
     - get / set <function-name>
 - interfaces: define a contract for the shape of an object, functions and classes
   - declaration merging (not interface exclusive): can be useful when you wanna add new properties or methods to the existing interface without modification.
 - generics: reusable code with various types
    - functions
    - classes
 - type narrowing
   - typeof
   - instanceof --> class or construct function
   - intersection types
 - declaration files


## nextjs
 - 


















