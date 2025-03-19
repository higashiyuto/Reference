selectとJavaScriptの連携

    ```html
    <select id="mySelect">
        <option value="a">A</option>
        <option value="b">B</option>
        <option value="c">C</option>
    </select>
    <button onclick="getValue()">選択値取得</button>
    <p id="output"></p>
    ```
    ```js
    function getValue(){
        let selectElement = document.getElementbyId("mySelect");
        let selectedValue = selectElement.value;
        document.getElementById("output").innerText = "選択された値: " + selectedValue;
    }
    ```
    -> 選択した値を取得して画面に表示