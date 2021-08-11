# Hajh Javascript Coding Conventions
- eslint-config-hajh-react 는 자바스크립트 및 리액트 코딩컨벤션을 지원하는 [eslint](http://eslint.org/) 룰 셋입니다.
- eslint-config-hajh-react 는 [eslint-config-airbnb-base](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base) 룰셋 기준으로 작성되었습니다.

> ### eslint-config-hajh-react는 2개의 룰 셋을 제공합니다.
> - ES6+ 룰 셋 : `hajh-react`
> - ES5 룰 셋 : `hajh-react/es5`

## Install
```
#npx install-peerdeps --dev eslint-config-hajh-react
```

## Usage
### ES6+ 룰 셋을 사용하는 경우
```
// .eslintrc 파일
{
  "extends": "hajh-react",
  "rules": {
    // 프로젝트별 적용할 Rules
  }
}
```

### ES6+ 와 React hooks(requires v16.8+)를 사용하는 경우
```
// .eslintrc 파일
{
  "extends": ["hajh-react", "hajh-react/hooks"],
  "rules": {
    // 프로젝트별 적용할 Rules
  }
}
```

### ES5 룰 셋을 사용하는 경우
```
// .eslintrc 파일
{
  "extends": "hajh-react/es5",
  "rules": {
    // 프로젝트별 적용할 Rules
  }
}
```

### ES5 와 React hooks(requires v16.8+)를 사용하는 경우
```
// .eslintrc 파일
{
  "extends": ["hajh-react/es5", "hajh-react/hooks"],
  "rules": {
    // 프로젝트별 적용할 Rules
  }
}
```

## Hajh JavaScript Style Guilde
상세한 내용은 다음의 JavaScript 스타일 가이드를 참조하세요  
### [Hajh JavaScript Style Guilde](STYLE_GUIDE.md)

## Hajh React Hooks Style Guide
상세한 내용은 다음의 JavaScript 스타일 가이드를 참조하세요
### [Hajh React Hooks Style Guilde](REACT_STYLE_GUIDE.md)


## License
`eslint-config-hajh-react` is released under the [MIT license](LICENSE).

```
Copyright (c) 2021 Hajh-React Corp.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
