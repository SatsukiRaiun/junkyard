# プログラミング言語 Euphoria
version 3.11

リファレンスマニュアル

© 2007 Rapid Deployment Software 著\
© 2009, 2010, 2026 Ninetailfox Software 訳

このマニュアルはライセンスに従う限り自由に複製や改訂ができます。

---

## 目次

[第一部・基本言語機能](refman_1.md)
 
 * 1\. [はじめに](refman_1.md)
     * 1.1 [サンプルプログラム](refman_1.md)
     * 1.2 [インストール](refman_1.md)
     * 1.3 [プログラムの実行](refman_1.md)
         * 1.3.1 [Windows上での実行](refman_1.md)
         * 1.3.2 [スワップファイルの使用](refman_1.md)
     * 1.4 [プログラムの編集](refman_1.md)
     * 1.5 [プログラムの配布](refman_1.md)
         * 1.5.1 [ライセンス](refman_1.md)

 * 2\. [言語仕様](refman_2.md)
     * 2.1 [オブジェクト](refman_2.md)
         * 2.1.1 [アトムとシーケンス](refman_2.md)
         * 2.1.2 [文字と文字列](refman_2.md)
         * 2.1.3 [コメント](refman_2.md)
     * 2.2 [演算式](refman_2.md)
         * 2.2.1 [関係演算子](refman_2.md)
         * 2.2.2 [論理演算子](refman_2.md)
         * 2.2.3 [算術演算子](refman_2.md)
         * 2.2.4 [シーケンスの演算](refman_2.md)
         * 2.2.5 [シーケンスの添字](refman_2.md)
         * 2.2.6 [シーケンスのスライス](refman_2.md)
         * 2.2.7 [シーケンスとアトムの連結 - '&' 演算子](refman_2.md)
         * 2.2.8 [シーケンスの構造](refman_2.md)
         * 2.2.9 [その他のシーケンス演算](refman_2.md)
             * [length](refman_2.md)
             * [repeat](refman_2.md)
             * [append / prepend](refman_2.md)
         * 2.2.10 [優先順位表](refman_2.md)
     * 2.3 [Euphoria と従来言語の比較](refman_2.md)
     * 2.4 [宣言](refman_2.md)
         * 2.4.1 [識別子](refman_2.md)
             * [手続き](refman_2.md)
             * [関数](refman_2.md)
             * [型](refman_2.md)
             * [変数](refman_2.md)
             * [定数](refman_2.md)
         * 2.4.2 [スコープ](refman_2.md)
         * 2.4.3 [変数の型指定](refman_2.md)
     * 2.5 [ステートメント](refman_2.md)
         * 2.5.1 [代入ステートメント](refman_2.md)
            * [代入演算子](refman_2.md)
         * 2.5.2 [手続きの呼び出し](refman_2.md)
         * 2.5.3 [if ステートメント](refman_2.md)
         * 2.5.4 [while ステートメント](refman_2.md)
            * [短絡評価](refman_2.md)
         * 2.5.5 [for ステートメント](refman_2.md)
         * 2.5.6 [return ステートメント](refman_2.md)
         * 2.5.7 [exit ステートメント](refman_2.md)
     * 2.6 [特殊上位ステートメント](refman_2.md)
         * 2.6.1 [include](refman_2.md)
         * 2.6.2 [with / without](refman_2.md)

 * 3\. [デバッグとプロファイル](refman_3.md)
     * 3.1 [デバッグ](refman_3.md)
         * 3.1.1 [トレーススクリーン](refman_3.md)
         * 3.1.2 [トレースファイル](refman_3.md)
     * 3.2 [プロファイル](refman_3.md)
         * 3.2.1 [時間プロファイリングに関する追記](refman_3.md)
 
[第二部 ・ライブラリルーチン](library.md)

 * 1\. [はじめに](library.md)
 * 2\. [アプリケーション向けルーチン](library.md)
     * 2.1 [定義済み型](library.md)
     * 2.2 [シーケンスの操作](library.md)
     * 2.3 [検索とソート](library.md)
     * 2.4 [パターンマッチング](library.md)
     * 2.5 [算術](library.md)
     * 2.6 [ビット論理演算](library.md)
     * 2.7 [ファイルとデバイス I/O](library.md)
     * 2.8 [マウスサポート (DOS32/Linux)](library.md)
     * 2.9 [オペレーティングシステム](library.md)
     * 2.10 [特殊機種依存ルーチン](library.md)
     * 2.11 [デバッグ](library.md)
     * 2.12 [グラフィックとサウンド](library.md)
     * 2.13 [マシンレベルインタフェース](library.md)
     * 2.14 [動的呼び出し](library.md)
     * 2.15 [C言語の関数の呼び出し](library.md)
     * 2.16 [マルチタスク](library.md)

 * 3\. ルーチンリスト (アルファベット順)
     * [A 〜 B](lib_a_b.md)
     * [C 〜 D](lib_c_d.md)
     * [E 〜 G](lib_e_g.md)
     * [H 〜 O](lib_h_o.md)
     * [P 〜 R](lib_p_r.md)
     * [S 〜 T](lib_s_t.md)
     * [U 〜 Z](lib_u_z.md)
 
→ [第一部・基本言語機能](refman_1.md)へ続きます...

---
