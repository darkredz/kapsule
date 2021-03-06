# Kapsule [![Build Status](https://travis-ci.org/traversals/kapsule.svg?branch=master)](https://travis-ci.org/traversals/kapsule) 

Minimalist dependency injection library for Kotlin.

**Note:** Kapsule is currently in pre-release stages of development. While every milestone build is well-tested and ready for use, breaking changes can be introduced without warning. Once version 1.0 is released, the changes will become more gradual.

Why create another dependency injection library? Here are the objectives pursued by Kapsule:

* Simple features that most projects will have use for
    - Alternative for projects whose dependency injection needs are quite basic
* Keep the method count to a minimum
    - Dependency injection shouldn't take thousands of methods to implement
* No annotation processing
    - No need for `lateinit` on properties and they can be private and read-only
* No magic, keep everything as a hard reference
    - Reading code is easier when you can click through all the references in your IDE
* Utilize the power of Kotlin
    - Use language features to simplify code instead of focusing on Java compatibility 

To accomplish all of these, Kapsule is based on [delegation](http://kotlinlang.org/docs/reference/delegation.html) and [delegated properties](http://kotlinlang.org/docs/reference/delegated-properties.html). 
  
## Documentation

* [User documentation](https://traversal.space/kapsule)
* [API reference](https://traversal.space/docs/kapsule)
* [Code samples](samples)

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file.
