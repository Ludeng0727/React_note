- React의 컨셉
    - 한 문장으로 정리 : A library for creating UI
    - 한 단어로 정리 : Components
    - Virtual DOM
    - 리액트는 데이터가 변경이 될 때 마다 어플리케이션 전체를 렌더링한다
    
- Component 구성요소
    - State
    - render
    
- React 개발환경 구성
    - Babel
        
        JavaScript Compiler.
        
        React jsx문법 ⇒ Vanilla JS
        
        최신버전 문법 ⇒ 구버전의 문법(ex. ES6 ⇒ ES5)
        
    - Webpack
        
        JS Application의 모든 코드들을 잘 모아서 합쳐준다.
        
    - Create React APP
        
        React개발 환경 설정을 위해서는 다양한 개발환경 설정이 필요.
        
        대표적으로 Babel, Webpack
        
        but, CRA로 간단하게 설정가능
        
- Tool 설명
    
    node.js : JavaScript 실행환경
    
    npm : Package Manger(라이브러리 관리 등)
    
    yarn : Package Manger(npm을 개선)
    
    jest : 유닛테스트 프레임워크
    
    PostCSS : CSS전처리기
    
    
- React 기본 개념
    - JSX
        
        JS 파일 위에서 HTML처럼 할 수 있도록 만들어 진 것
        
    - State
        
        Component 안에서 사용하는 데이터 객체
        
    - Props
        
        함수의 매개변수처럼 Component에 데이터를 넘겨줌
        
    - Class Component
        
        
    - Function Component
        
        React Hook을 이용해 State, LifeCycle을 추가 가능
        
    - React Hook
        
        기존의 함수형 컴포넌트에서 State와 LifeCycle method를 잘 이용할 수 있게 만들어진 아이이다.
        
        useState() API이용
        
        ex. const[count, setCount] = useState(default);
        
        useEffect() ⇒ componentDidMount + componentDidUpdate
        
    - Lifting State up
        
        자식 컴포넌트의 state를 부모 컴포넌트가 사용한다면,
        
        자식 컴포넌트의 state를 부모 컴포넌트의 state로 올리고,
        
        자식 컴포넌트에게는 prop으로 전달
        
    - Ref
        
        Component에 접근할 때 사용
        
        클래스 컴포넌트 React.createRef()를 사용하자
        
        함수형 컴포넌트에서는 useRef()를 사용하자
        
    - Pure Component
        
        Component의 state나 props가 변화가 없다면 render함수 호출XX
        
    - memo
        
        Function  Component를 Pure Component로 바꿔주는 역할
        
        Pure Component와 비슷
        
    - LifeCycle method
