## 타입스크립트가 필요한 이유?

- 실수방지

  - 함수, 컴포넌트 등의 타입 추론이 되다보니, 만약에 우리가 사소한 오타를 만들면 코드를 실행하지 않더라도 IDE 상에서 바로 알 수 있게 됩니다. 그리고, 예를 들어 null 이나 undefined 일 수도 있는 값의 내부 값 혹은 함수를 호출한다면 (예: 배열의 내장함수) 사전에 null 체킹을 하지 않으면 오류를 띄우므로 null 체킹도 확실하게 할 수 있게 됩니다.

- IDE 를 더욱 더 적극적으로 활용 (자동완성, 타입확인)
  - TypeScript 를 사용하면 자동완성이 굉장히 잘됩니다. 함수를 사용 할 때 해당 함수가 어떤 파라미터를 필요로 하는지, 그리고 어떤 값을 반환하는지 코드를 따로 열어보지 않아도 알 수 있습니다. 추가적으로, 리액트 컴포넌트의 경우 해당 컴포넌트를 사용하게 될 때 props 에는 무엇을 전달해줘야하는지, JSX 를 작성하는 과정에서 바로 알 수 있으며, 컴포넌트 내부에서도 자신의 props 에 어떤 값이 있으며, state 에 어떤 값이 있는지 알 수 있습니다. 또한, 리덕스와 함께 사용하게 될 때에도 스토어 안에 어떤 상태가 들어있는지 바로 조회가 가능해서 굉장히 편리합니다.
