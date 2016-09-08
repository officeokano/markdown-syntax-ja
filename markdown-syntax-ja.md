# マークダウン書式一覧
日本語版

# 章と改行

    1行以上の空行を挟むと章区切り  
    空白文字とタブだけの行も空行  
    日本語の全角スペースは空白ではなく文字  
    文末に2つ以上の空白文字を入れると強制改行

# 見出し

    # H1
    ## H2
    ### H3
    #### H4
    ##### H5
    ###### H6

    # で囲んでもいい #
    ### 前後で#の数が違う場合は前側優先 #

    H1は下行=でも指定可  
    ===================
    H2は下行-でも指定可
    ----
    文字数は合わなくても可

# 引用

    > 行頭に>で引用  
    二行目は記号なしでも可

    > 空行を挟んでも引用は続く
    >> 入れ子にもできる

# 箇条書き

    - で箇条書き
    + でも箇条書き
    * でもよい

# ナンバリング

    1. でナンバリング
    - 2行目からは記号でも可
    5. 数字が飛んでいても
    3. 順番が逆でも
    4. ちゃんと並び替える
    ナンバリングされたくなければピリオドをエスケープ

# コード

    行頭4個以上の空白でソースコード
    `で囲んだ文字もソース`

# 区切り線

    *または-3個以上連続で水平線
    - - - 間に空白が入っても可
    *** 連続しても可

# リンク

    [リンク文字](リンクURL "タイトル")
    <リンクURLがそのまま見えてリンク>
    [リンク文字][id]
    URLを文末に書くこともできる
    [id]: リンクURL "タイトル"
    タイトルは省略可

# 強調

    *emphasis(たいてい斜体)*
    **strong(たいてい太字)**
    ***両方適用***
    _でもよい_

# 画像

    ![](画像URL)
    ![Alt text](画像URL "タイトル")
    ![Alt text][id]
    画像URLを文末に書くこともできる
    [id]: 画像URL "タイトル"
    Alt textとタイトルは省略可

# エスケープ

    以下の記号はを文中で使うときは\でエスケープ
    \   backslash
    `   backtick
    *   asterisk
    _   underscore
    {}  curly braces
    []  square brackets
    ()  parentheses
    #   hash mark
    +	plus sign
    -	minus sign (hyphen)
    .   dot
    !   exclamation mark

markdown-syntax-ja by H Okano  
    h.okano@gmail.com  
    [twitter](https://twitter.com/okano)  
    [telegram](https://telegram.me/lvmdc)  
    [messenger](https://m.me/okano)  
Released for free under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](http://creativecommons.org/licenses/by-sa/4.0/)