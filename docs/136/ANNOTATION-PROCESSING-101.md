# [ANNOTATION PROCESSING 101](http://hannesdorfmann.com/annotation-processing/annotationprocessing101/)

최근에 작성된 글(2015.01.10)임에도 변경된 사항이 있다.

	내용 중에도 언급되어 있는데 Java 파일을 작성하기 위해 사용된 JavaWriter Library 가 JavaPoet 으로 변경되었다. 
    (하지만 Maven Repository 에서 여전히 예전 버전의 JavaWriter 를 받을 수 있어서 그대로 따라해도 무방해 보인다.)

내용은 크게 세 가지로 나눌 수 있다.

1. AbstractProcessor 를 상속받아 Processor 를 만드는 법
2. 자신이 만든 Processor 를 등록하는 법
3. 예제 (PizzaStore)

예제에서는 2번에 나온 등록 방법 대신 Google 에서 만든 @AutoService 를 이용해서 등록한다.

구현은 Error Handling 과 Java File 생성(Code Generation) 부분이 있다.

### Processor 와 Annotation 분리

	65k method limit (a android .dex file can only address 65,000 methods)

예) Guava

	Guava 는 20,000 여 개의 method 를 가지고 있다.

### 활용 방안 소개

ButterKnife, FragmentArgs

### 결론


