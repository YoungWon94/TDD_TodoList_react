
# TDD_TodoList_react

- 설치
    >npm install --save @testing-library/jest-dom  
    npm install --save @testing-library/react  
    npm install --save @types/jest


- 준비  
src/`setupTests.js` 파일 작성
    ```js
    import "@testing-library/jest-dom/extend-expect";  
    import "@testing-library/react";
    ```

- 테스팅(실패) -> 코드작성 -> 테스팅(성공) -> 리팩토링  
