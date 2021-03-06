---
layout: post
title: 디자인 패턴의 종류
categories:
  - study
tags:
  - study
---

# 디자인 패턴
- 소프트웨어 설계시 특정 맥락에서 자주 발생하는 문제들에 대한 해결책을 정리해 놓은 패턴

# 디자인 패턴의 구조
## 콘텍스트(Context)
  - 패턴이 적용될 수 있는 상황 또는 패턴이 유용하지 않은 상황
  
## 문제(problem)
  - 패턴이 적용되어 해결될 필요가 있는 여러 이슈들을 기술
  - 제약 사항과 영향력을 고려 해야 함
  
## 해결(solution)
  - 문제 해결을 위한 설계를 구성하는 요소들과 관계, 책임, 협력 관계를 기술.
  - 구체적인 방법이나 언어에 의존적이지 않으며 다양한 상황에 적용할 수 있는 일종의 템플릿.
  
# 디자인 패턴의 종류
## GoF 디자인 패턴
- **G**ang **o**f **F**out 라 불리는 사람들: Erich Gamma, Richard Helm, Ralph Johnson, John Vissides
- 소프트웨어 개발 영역에서의 디자인 패턴을 구체화하고 체계화한 사람들
- 23가지의 디자인 패턴을 정리하고 각각의 디자인 패턴을 생성(Creational), 구조(Structural), 행위(Behavioral)의 3가지로 분류.

### 생성(Creational) 패턴
- 객체 생성에 관련된 패턴
- 객체의 생성과 조합을 캡슐화해 특정 객체가 생성되거나 변경 되어도 프로그램 구조에 영향을 크게 주지 않도록 유연성 제공 목적

### 구조(Structural) 패턴
- 클래스나 객체를 조합해 더 큰 구조를 만드는 패턴
- 서로 다른 인터페이스를 지닌 두개의 객체를 묶어 단일 인터페이스를 제공하거나 객체들을 묶어 새로운 기능을 제공.

### 행위(Behavioral) 패턴
- 객체나 클래스 사이의 알고리즘이나 책임 분배에 관련된 패턴
- 한 객체가 혼자서 수행할 수 없는 작업을 여러개의 객체로 어떻게 분배하는지, 또 그렇게 하면서도 객체 사이의 결합도를 최소화 하는 목적

# 디자인 패턴의 종류 및 설명
## 생성(Creational) 패턴

### 추상 팩토리(Abstract Factory)

### 팩토리 메서드(Factory Method)

### 싱글턴(Singleton)

### 빌더(Builder)

### 프로토타입(Prototype)

## 구조(Structural) 패턴
### 컴퍼지트(Composite)
- 어떤 컴포넌트에 속하는 여러개의 클래스들이 있을때, 여기에 속한 어떤 클래스(Composite)가 자기 자신 혹은 다른 클래스를 가질 수 있는 구조
- 같은 개념의 클래스들 간에 소유 개념을 나타낸 트리 형태로 묶고 싶을 때 사용

### 데코레이터(Decorator)
- 기능을 담당하는 클래스들과 이 기능을 적용할 클래스를 분리한 뒤, 필요에 따라 동적으로 각 기능을 적용할 수 있는 구조
- 주요 기능에 경우에 따라 부가적인 기능을 추가하거나 빼고 싶을 때 사용
- 프록시와의 차이: 주요 기능에 부가 기능을 추가하여 주요 기능을 변경

### 어댑터(Adapter)
- 서로 다른 두 클래스가 있고, 이 둘은 그대로 둔 채 이 둘의 인터페이스를 연결하고자 어댑터 클래스를 만들어 사용하는 구조
- 이미 정의된 3자의 인터페이스를 자신의 인터페이스의 모양으로 **인터페이스 변경** 하고 싶을때 사용한다

### 브리지(Bridge)

### 퍼사드(Facade)

### 플라이웨이트(Flyweight)

### 프록시(Proxy)
- 구체적인 업무를 담당하고 있는 클래스에 접근하기 전, 간단한 사전 작업을 처리하는 클래스(Proxy)를 두는 구조
- 주요 기능이 요청을 받아 수행하기 전에, 이 요청에 대한 부가적인 전처리들을 수행하는 로직을 세우고 싶을 때 사용
- 데코레이터와의 차이: 주요 기능에 대한 추가 동작

## 행위(Behavioral) 패턴
### 책임 연쇄(Chain of Responsibility)

### 커맨드(Command)
- 특정 객체에 대한 커맨드를 객체화하여 이 커맨드 객체를 필요에 따라 처리하는 패턴

### 인터프리터(Interpreter)

### 이터레이터(Iterator)

### 미디에이터(Mediator)

### 메멘토(Memento)

### 옵저버(Observer)

### 스테이트(State)

### 스트래티지(Strategy)

### 템플릿 메서드(Template Method)

### 비지터(Visitor)
