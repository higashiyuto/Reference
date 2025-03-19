optionタグでグループ化

    <optgroup>を使うと、関連する選択肢をグループ化できる

    ```html
    <select>
        <optgroup label="フルーツ">
            <option value="apple">りんご</option>
            <option value="banana">バナナ</option>
        </optgroup>
        <optgroup label="野菜">
            <option value="carrot">にんじん</option>
            <option value="spinach">ほうれん草</option>
        </optgroup>
    </select>
    ```
    -> フルーツ、野菜の見出しで区切られる