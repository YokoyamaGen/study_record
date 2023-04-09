以下、記事を学習
https://qiita.com/jnchito/items/2e79a1abe7cd8214caa5

- マッチャ
  to XXXのXXXのことを指す。想定値と実際の値を比較した結果のオブジェクトを返す。
  - eq
    - 値がイコールかどうか。値がイコールかを調べる。
  - be
    - 不等号や大小を使用した比較をするのに使用する。不等号や大小なしでも使用でき、その際には同一のインスタンスを調べる。
  - be_truthy、be_falthy
    - rubyの言語仕様として、falseやnilの時はfalseで、それ以外はtrueとなる。expect(1).to be_truthy、
      expect(nil).to be_falseyはどちらもテストがパスする。
