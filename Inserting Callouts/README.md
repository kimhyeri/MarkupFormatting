# Quick Help Syntax

## Attention
>  Attention을 사용해 quick help에 call out을 추가하세요. 

- Attention앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the attention field

 - Attention: What I if told you
 you read this line wrong?
*
```

## Author
>  Author을 사용해 quick help에 call out을 추가하세요. 

- Author앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the author field

 - Author: William Shakespeare
*/
```

## Authors
>  Authors를 사용해 quick help에 call out을 추가하세요. 

- Authors앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. (각 저자 이름 사이에 빈줄이 있어야합니다.)
```
/**
 An example of using the authors callout

 - Authors:
  Plato

  Aristotle

  Other amazing
  classical folk
*
```

## Bug
>  Bug를 사용해 quick help에 call out을 추가하세요. 

- Bug앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the bug field

 - Bug:
 [*bugExample* contains a memory leak](BugDB://problem/1367823)

 - Bug:
 [Passing a `UIViewController` crashes *bugExample*](BugDB://problem/2274610)
*/
```

## Complexity
>  Complexity를 사용해 quick help에 call out을 추가하세요. 메서드 또는 함수의 알고리즘 복잡도를 표시합니다.

- Complexity앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the complexity field

 - Complexity:
 The method demonstrates an inefficient way to sort
 using an O(N\*N\*N) (order N-cubed) algorithm
*/
```

## Copyright
>  Copyright를 사용해 quick help에 call out을 추가하세요. 저작권 정보를 표시합니다.

- Copyright앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the copyright field

 - Copyright: Copyright © 1215
 by The Group of Barrons
*/
```

## Date
>  Date를 사용해 quick help에 call out을 추가하세요.

- Date앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the date field

 Last date this example was changed
 - Date: August 19, 2015

 Days the method produces special results
 - Date: 12/31
 - Date: 03/17
*/
```

## Experiment
>  Experiment를 사용해 quick help에 call out을 추가하세요. 

- Experiment앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the experiment field

 - Experiment: Pass in a string in the present tense
 - Experiment: Pass in a string with no vowels
 - Experiment:
 Change the third case statement to work only with consonants
*/
```

## Important
>  Important를 사용해 quick help에 call out을 추가하세요. 사용자가 수행하려는 작업에 안좋은 영향을 미칠 수 있는 정보를 표시해줍니다.

- Important앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the important field

 - Important:
 "The beginning is the most important part of the work."
 \
 –Plato
*/
```

## Invariant
>  Invariant를 사용해 quick help에 call out을 추가하세요. 참이 보장되는 조건을 나타냅니다. 

- Invariant앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the invariant field

 - Invariant:
 The person reference will not change during the execution of this method
*/
```

## Note
>  Note를 사용해 quick help에 call out을 추가하세요. 

- Note앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the note field

 - Note:
 This method returns an estimate.
 Use `reallyAccurateReading` to get the best results.
 */
```

## Precondition
>  Precondition을 사용해 quick help에 call out을 추가하세요. 작동되는 조건을 나타냅니다.

- Precondition앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the precondition field

 - Precondition: The `person` property must be non-nil.
 - Precondition: `updatedAddress` must be a valid address.
*/
```

## Postcondition
>  Postcondition을 사용해 quick help에 call out을 추가하세요. 실행이 완료될 때 보장되는 값을 갖는 조건을 나타냅니다. 

- Postcondition앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the postcondition field

 - Postcondition:
 After completing this method the billing address for
 the person will be set to `updatedAddress` if it is valid.
 Otherwise the billing address will not be changed.
*/
```

## Remark
>  Remark를 사용해 quick help에 call out을 추가하세요. 

- Remark앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the remark field

 - Remark:
 The performance could be reduced from N-squared to
 N-log-N by switching patterns.
*/
```

## Requires
>  Requires을 사용해 quick help에 call out을 추가하세요. 

- Requires앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the requires field

 - Requires: `start <= end`.
 - Requires: `count > 0`.
*/
```

## See Also
>  See Also를 사용해 quick help에 call out을 추가하세요. 다른 정보에 대한 참조를 추가할 수 있습니다.

- See Also앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the SeeAlso field

 - SeeAlso:
 [My Library Reference](https://example.com)
*/
```

## Since
>  Since를 사용해 quick help에 call out을 추가하세요. 사용할 수 있게 된 시기에 대한 정보를 추가합니다. 정보 예로는 (날짜, 프레임워크 버젼 및 운영 체제 버젼)이 있습니다.

- Since앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the since field

 - Since: First available in Mac OS 7
*/
```

## Version
>  Version을 사용해 quick help에 call out을 추가하세요. 

- Version앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the version field

 - Version: 0.1 (61A329)
*/
```

## Warning
>  Warning을 사용해 quick help에 call out을 추가하세요. 

- Warning앞에 ( * ), ( + ), ( - )를 사용할 수 있습니다. 
```
/**
 An example of using the warning field

 - Warning:
 Not all code paths for this method have been tested
*/
```
