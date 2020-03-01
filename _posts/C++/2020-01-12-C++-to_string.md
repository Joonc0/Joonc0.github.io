---
title:  "[C++] to_string"
last_modified_at: 2020-01-12T17:01:17-04:00
categories: 
  - C++
tags:
  - C++
  - string

---

# to_string 사용법

-   ``` #include <string>``` 헤더를 사용한다.
- 기능 : 다른 자료형을 ``string`` 으로 만들어 준다.

# Example

```c++  
	int a = 1;
	int b = 2;
	string ab = to_string(a) + to_string(b);	
```

#### ab의 값은 ```12``` 가 된다.

