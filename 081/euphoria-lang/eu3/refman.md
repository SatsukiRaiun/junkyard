\
プログラミング言語 Euphoria\
\
version 3.1\
\
リファレンスマニュアル\

 

\(c\) 2007 Rapid Deployment Software (原著)\
(c) 2009,2010, Ninetailfox Software (日本語版担当)\

 

このマニュアルはライセンスに従う限り\
自由に複製や改訂ができます。\

 

------------------------------------------------------------------------

目次

[第一部 - 言語主要部](refman_1.htm)

1\. [はじめに](refman_1.htm)

:   

    1.1 [サンプルプログラム](refman_1.htm#1)

    :   

    1.2 [インストール方法](refman_1.htm#2)

    :   

    1.3 [プログラムの実行方法](refman_1.htm#3)
    :   1.3.1 [Windows上での実行方法](refman_1.htm#31)
    :   1.3.2 [スワップファイルの使用方法](refman_1.htm#32)
    :   

    1.4 [プログラムの編集方法](refman_1.htm#4)

    :   

    1.5 [プログラムの配布方法](refman_1.htm#5)
    :   1.5.1 [ライセンス](refman_1.htm#51)

2\. [言語仕様](refman_2.htm)

:   

    2.1 [オブジェクト](refman_2.htm#1)
    :   2.1.1 [アトムとシーケンス](refman_2.htm#1)
    :   2.1.2 [文字と文字列](refman_2.htm#11)
    :   2.1.3 [コメント](refman_2.htm#12)
    :   

    2.2 [演算式](refman_2.htm#2)
    :   2.2.1 [関係演算子](refman_2.htm#23)
    :   2.2.2 [論理演算子](refman_2.htm#24)
    :   2.2.3 [算術演算子](refman_2.htm#25)
    :   2.2.4 [シーケンスの演算](refman_2.htm#26)
    :   2.2.5 [シーケンスの添字](refman_2.htm#21)
    :   2.2.6 [シーケンスのスライス](refman_2.htm#22)
    :   2.2.7 [シーケンスとアトムの連結 - \'&\' 演算子](refman_2.htm#27)
    :   2.2.8 [シーケンスの構造](refman_2.htm#28)
    :   2.2.9 [その他のシーケンス演算](refman_2.htm#29)
        - [length](refman_2.htm#291)
        - [repeat](refman_2.htm#292)
        - [append / prepend](refman_2.htm#293)
    :   2.2.10 [優先順位表](refman_2.htm#2A)
    :   

    2.3 [Euphoriaと従来の言語との比較](refman_2.htm#3)

    :   

    2.4 [宣言](refman_2.htm#4)
    :   2.4.1 [識別子](refman_2.htm#41)
        - [手続き](refman_2.htm#411)
        - [関数](refman_2.htm#412)
        - [型](refman_2.htm#413)
        - [変数](refman_2.htm#414)
        - [定数](refman_2.htm#415)
    :   2.4.2 [スコープ](refman_2.htm#42)
    :   2.4.3 [変数の型指定](refman_2.htm#43)
    :   

    2.5 [構文](refman_2.htm#5)
    :   2.5.1 [代入構文](refman_2.htm#assign)
        - [代入演算子](refman_2.htm#assignop)
    :   2.5.2 [手続きの呼び出し](refman_2.htm#proc)
    :   2.5.3 [if構文](refman_2.htm#if)
    :   2.5.4 [while構文](refman_2.htm#while)
        - [短絡評価](refman_2.htm#shortcir)
    :   2.5.5 [for構文](refman_2.htm#for)
    :   2.5.6 [return構文](refman_2.htm#return)
    :   2.5.7 [exit構文](refman_2.htm#exit)
    :   

    2.6 [特殊上位構文](refman_2.htm#6)
    :   2.6.1 [include](refman_2.htm#61)
    :   2.6.2 [with / without](refman_2.htm#62)

3\. [デバッグとプロファイル](refman_3.htm)

:   

    3.1 [デバッグ](refman_3.htm#1)
    :   3.1.1 [トレーススクリーン](refman_3.htm#11)
    :   3.1.2 [トレースファイル](refman_3.htm#12)

    3.2 [プロファイル](refman_3.htm#2)
    :   3.2.1
        [時間プロファイリングに関していくつかの追加の注意点](refman_3.htm#21)

 

[第二部 - ライブラリルーチン](library.htm)

1\. [はじめに](library.htm)

2\. [アプリケーション向けルーチン](library.htm#2)

2.1 [定義済み型](library.htm#predefined)

:   

2.2 [シーケンスの操作](library.htm#seq_manip)

:   

2.3 [検索とソート](library.htm#srch_srt)

:   

2.4 [パターンマッチング](library.htm#pattern_m)

:   

2.5 [算術](library.htm#math)

:   

2.6 [ビット論理演算](library.htm#bitw_logic)

:   

2.7 [ファイルとデバイスI/O](library.htm#i_o)

:   

2.8 [マウスサポート(DOS32/Linux)](library.htm#mouse_spt)

:   

2.9 [オペレーティングシステム](library.htm#op_sys)

:   

2.10 [特殊機種依存ルーチン](library.htm#machine_dep)

:   

2.11 [デバッグ](library.htm#debugging)

:   

2.12 [グラフィックとサウンド](library.htm#gr_sound)

:   

2.13 [マシンレベルインタフェース](library.htm#m_level_i)

:   

2.14 [動的呼び出し](library.htm#dyn_call)

:   

2.15 [C言語の関数の呼び出し](library.htm#call_c_func)

:   

2.16 [マルチタスク](library.htm#tasking)

:   

3\. ルーチンリスト(アルファベット順)

[A から B まで](lib_a_b.htm)

:   

[C から D まで](lib_c_d.htm)

:   

[E から G まで](lib_e_g.htm)

:   

[H から O まで](lib_h_o.htm)

:   

[P から R まで](lib_p_r.htm)

:   

[S から T まで](lib_s_t.htm)

:   

[U から Z まで](lib_u_z.htm)

:   

 

[第一部 - 言語主要部](refman_1.htm) に続きます\...

 
