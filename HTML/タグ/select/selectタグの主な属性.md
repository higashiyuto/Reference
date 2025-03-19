selectタグの主な属性

<select>タグの主な属性

    name
    ・フォーム送信時のキー名として使われる

    ```html
    <select name="country">
        <option value="japan">日本</option>
        <option value="usa">アメリカ</option>
    </select>
    ```
    送信時のデータ: country=japanなど

    id
    ・JavaScriptやCSSで特定の<select>要素を操作するための識別子

    size
    ・表示する選択肢の数を指定

    ```html
    <select size="3">
        <option>りんご</option>
        <option>バナナ</option>
        <option>ブドウ</option>
        <option>メロン</option>
    </select>
    ```
    デフォルトのドロップダウンではなく、リスト表示される

    multiple
    ・複数選択を可能にする

    ```html
    <select multiple>
        <option>りんご</option>
        <option>バナナ</option>
        <option>ブドウ</option>
    </select>