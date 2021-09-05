# HOC

 1. Use HOCs For Cross-Cutting Concerns
 2. Don't Mutate the Original Components , Use Composition.
 3. Pass Unrelated props through toe the Wrapped Component
 4. Maximizing Composability
 5. Wrap the Display Name for Easy Debugging


 - [Cross-Cutting Concerns](https://ko.wikipedia.org/wiki/%ED%9A%A1%EB%8B%A8_%EA%B4%80%EC%8B%AC%EC%82%AC)
 - [react-document-Cross-Cutting-Conecrns](https://ko.reactjs.org/docs/render-props.html#use-render-props-for-cross-cutting-concerns)
 - [react-document-HOC](https://ko.reactjs.org/docs/higher-order-components.html#dont-mutate-the-original-component-use-composition)


## warning

  1. Don't Use HOCs inside the render Method
  2. Static Method Must Be Copied Over	( using hoistStatics ) ( hoist-non-react-statics)
  3. Refs Aren't Passed through (feat. React.forwardRef)
  * [hoist-non-react-static](https://www.npmjs.com/package/hoist-non-react-statics)
  * [react-document](https://ko.reactjs.org/docs/higher-order-components.html)