### 학습한 내용 기록하기


#2020-0204



▷무엇인지는 알고는 있지만 정확하게는 잘몰랐던 웹팩에 대해서 알아보는 시간을 가졌다. 내가 좋아하는 사이트중 하나인 생활코딩(https://opentutorials.org) 에서 웹팩을 다룬 강의가 업로드가 완료되었다는 소식을 듣고, 바로 접속을 해서 강의를 들었다. 아니나 다를까 강의는 정말 이해하기 쉽게 잘만들어져 있었고, 마지막 강의가 끝난후 내 머릿속에는 웹팩이라는 저장소가 이미 자리를 잡고 있었다. 기초적인 내용이었지만 많은 성취감을 느꼈고, 이것을 토대로 얼른 웹팩을 활용해서 프로젝트를 만들어보자고 결심했다!



#2020-0206

-CSS의 transition.
-SCSS의 다루는 방법.



#2020-0208

-자바스크립트 Immutablity
문자열의 메소드와 달리 배열(객체)의 메소드는 직접 대상을 변경
문자열은 변경할 수 없는 immutable value, 객체는 변경 가능한 값
let user1 = {'name': 'lee'};
let user2 = user1;
user2.name = 'cho';
user2.name === user1.name; //true
user1과 user2가 같은 어드레스를 참조하고 있기 때문.
immutable.js의 사용.



#2020-0209

-자바스크립트 prototype



#2020-0210

-리액트의 학습을 위한 원하는 카테고리의 사진들을 볼 수 있는 간단한앱만들기 시작.

prop-types의 사용법.


#2020-0211

-헷갈렸던 git의 사용법에 대해 다시 상기해보는 시간. 

-자바스크립트 scope(전역, 지역, 비 블록 레벨, 함수 레벨, 렉시컬).

※렉시컬 스코프는 함수의 선언 위치에 따라 결정된다는 것이다.

-자바스크립트 strict mode.


#2020-0213

-자바스크립트 this 
자바스크립트에서의 this 는 자바의 this 와 비교해볼 수 있다. 자바의 this는 인스턴스 자신을 가리키는 참조변수이다. 하지만 자바스크립트의 this는 해당 함수의 호출 방식에 따라 this에 바인딩 되는 객체가 정적이 아닌 동적으로 결정된다.

※기본적으로 this는 전역객체(Global object)에 바인딩된다.(ex 내부함수, 오브젝트 메소드의 내부함수, 콜백함수)

내부함수는 어디에서 선언되었든지 this는 전역객체를 바인딩한다.

※this를 명시적으로 바인딩할 수 있는 방법은 apply, call, bind 메소드를 사용하는 방법과 오브젝트 메소드안에서 this를 변수선언하는 방법이 있다.

※화살표 함수는 일반 함수와는 다르게 고유한 this를 가지지 않으며 화살표 함수안에서 this를 사용하면, 외부에서 this의 값을 가져온다. 

-자바스크립트 실행 컨텍스트
 

2020-0216

-자바스크립트 closure
클로저는 함수와 그 함수가 선언됐을 때의 렉시컬 환경과의 조합이다.(https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)

클로저는 현재상태를 기억하고 상태가 변경되어도 최신상태를 유지하는데 매우 유용.     

즉시실행함수 변수 할당.

-이스케이프 처리, 정규표현식.

-git config core.autocrlf false|true (LF will be replaced by CRLF in git 문제에 대한 일시적인 해결...)



2020-0218

-자바스크립트 닌자코드.., 테스트 자동화


2020-0220 

-자바스크립트 String 레퍼 객체
1.String 객체는 String 생성자함수를 통해 생성할 수 있다. 이때 전달된 인자는 모두 문자열로 반환됨.
2.문자열 내의 문자갯수를 반환한다. String 객체는 length 프로퍼티를 소유하고 있으므로 유사배열 객체.
3.문자열은 변경불가능한 원시값이기 때문에 String 객체의 모든 메소드는 언제나 새로운 문자열을 반환함.
(String.prototype.(charAt(index), concat(str1[,str2,...,strN]), indexOf(searchString[, fromIndex]), replace(searchValue, replacer), split([separator[, limit]]), substring(start[, end]), slice(start: number, end: number),toLowerCase(), toUpperCase(), trim(), repeat(count: number), includes(searchString: string, position: number))
-자바스크립트 
[*poiemaWeb]

2020-0223
-자바스크립트 배열, 배열고차함수  

2020-0224
-Sass



