                  ARM-M依存部(ARMCLANG版) ディレクトリ解説

                                   Last Modified:2018 Apr 19 19:29:33


本ディレクトリ（./arch/arm_m_armclang）は，armv7mアーキテクチャのコア
及び，armv7mアーキテクチャのコアを用いたチップに依存し，コンパイラとし
てARMCLANGを対象した記述を置くためのディレクトリである．

GCC版と共有するファイルはARM依存部(GCC版) ディレクトリ，ARM依存部
(ARMCC版) ディレクトリのいずれかに配置する．

common以下のファイルで共有するファイルはARM依存部(GCC版)に配置している
．

その他のルールはGCC版と同様である．
