//==============================================================================
// XSL スタイルシートの適用

Copyright(C) 2003 Iwanaga Nobuyuki
e-mail   : iwanaga@ise.eng.osaka-u.ac.jp
web page : http://www-ise2.ist.osaka-u.ac.jp/~iwanaga/

//----------------------------------------------------------
// 概要

- コマンドライン引数でフォルダ名を指定する。
- 指定したフォルダ内にある全ての XML ファイルに対して XSL 変換をかける。
  （サブフォルダ中のファイルを含む）
- <?xml-stylesheet?> 処理命令中の href 擬似属性で指定した
  XSL スタイルシートを使って XSL 変換を行う。
- 出力ファイル名は元の XML ファイル名の拡張子を
  .xml から .html に変更したもの。
