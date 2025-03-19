selectタグ

    selectタグは、HTMLのフォーム要素の一つで、
    ユーザに選択肢のリストを提供するドロップダウンメニューを
    作成するために使用される

    1. <select>タグの基本構造

    ```html
    <select id="fruit" name="fruit">
        <option value="apple">りんご</option>
        <option value="banana">バナナ</option>
        <option value="grape">ブドウ</option>
    </select>

    ```
    ・<select>: ドロップダウンメニューを作成する要素
    ・id="fruit": JavaScriptやラベルとの連携に使う識別子
    ・name="fruit"：フォーム送信時のキー名
    ・<option>: 各選択肢
        ・value="apple": フォーム送信時に使われる値
        ・りんご:実際にユーザが見る表示テキスト

[selectタグの主な属性](./selectタグの主な属性.md)
[optionタグの詳細](./optionタグの詳細.md)
[optgroupタグでグループ化](./optgroupタグでグループ化.md)
[selectとJavaScriptの連携](./selectとJavaScriptの連携.md)