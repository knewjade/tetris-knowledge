========================
パフェ2回目：Tなし
========================

**5地形でパフェ1回目テンプレ＆グレースシステムの残りミノはカバーできます**

対応表
===========================================

.. table::
   :widths: 10

   ============== ===== ===== ===== ===== =====
    IO**          A'    B'    C'    D'    E'
   ============== ===== ===== ===== ===== =====
    IOLJ            O
    IOSZ                                    O
    IOLS = IOJZ                       O
    IOLZ = IOJS         \(O\)         O
   ============== ===== ===== ===== ===== =====

.. table::
   :widths: 10

   ============== ===== ===== ===== ===== =====
    I***          A'    B'    C'    D'    E'
   ============== ===== ===== ===== ===== =====
    ILJS = ILJZ   \(O\)         O           O
    ILSZ = IJSZ           O
   ============== ===== ===== ===== ===== =====

.. table::
   :widths: 10

   ============== ===== ===== ===== ===== =====
    O***          A'    B'    C'    D'    E'
   ============== ===== ===== ===== ===== =====
    OLJS = OLJZ    O
    OLSZ = OJSZ           O
   ============== ===== ===== ===== ===== =====

.. table::
   :widths: 10

   ============== ===== ===== ===== ===== =====
    \****         A'    B'    C'    D'    E'
   ============== ===== ===== ===== ===== =====
    LJSZ                        O
   ============== ===== ===== ===== ===== =====

----

パターンA'
===========================================

.. |a2_fig01| image:: img/a2/fig_001.png
   :scale: 50
.. |a2_fig02| image:: img/a2/fig_002.png
   :scale: 50
.. |a2_fig03| image:: img/a2/fig_003.png
   :scale: 50
.. |a2_fig04| image:: img/a2/fig_004.png
   :scale: 50
.. |a2_fig05| image:: img/a2/fig_005.png
   :scale: 50
.. |a2_fig06| image:: img/a2/fig_006.png
   :scale: 50
.. |a2_fig07| image:: img/a2/fig_007.png
   :scale: 50
.. |a2_fig08| image:: img/a2/fig_008.png
   :scale: 50
.. |a2_fig09| image:: img/a2/fig_009.png
   :scale: 50
.. |a2_fig10| image:: img/a2/fig_010.png
   :scale: 50

.. |a2_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@LhBthlFeg0BtglRpDei0glRpJeAglLhhlxwGeRpHeB?PMeAAeLhAPAeRaFeAPxSAtFeAPAehlLeAAeMhBPHeRpGexw?hlLeAAAMhxhHeBPAeRpDeTLhWJeAAALhgWwSQawSQpg0EeR?axSEeRaBexwJeAAAOhRpHexhIehWJeAAALhhlBehHEexwhl?Eeh0BexSJeAAALhBtglgWFeAtBPhWAPDeQaAPglyhJeAAAL?hhHRphlEeBtRaFeRpxhKeAAA" target="_blank">
     セットアップ：テト譜
   </a>

.. |a2_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@LhD8FeF8DeF8JeAg0YAlfT6BY0DfEToXOBlvs2AUDE?fETo/ACYgwwFeBtxwGeBtwwTezhRpwwGeRpxwR4FewwR4Qe?AAtAAOgAtFeh0AtQaFeglAPQawSFeg0hWwSPeQ4IeglQ4hl?FewhglwDQLFewhRaglPeAAeNgglgWFegHgWAegWFegHwwAe?glFeQaRpQeQag0HeQaAewwgWFewhAewwgWGeRaQpPeAAeNg?gWQpHewhQpFeAtQaRpFeQahlQpPeQagHHeQagWHexSglQ4F?eSaglPeAAeOgQaFeglAPRaFegWglRaFegWQLwSwhPeglIeh?lwDg0FehWQLQaFewSQpglQaPeAAe" target="_blank">
      消しかた：テト譜
   </a>

.. container:: field_images

  |a2_fig01|
  |a2_fig02|
  |a2_fig03|
  |a2_fig04|
  |a2_fig05|
  |a2_fig06|
  |a2_fig07|
  |a2_fig08|
  |a2_fig09|
  |a2_fig10|

|

I と O のおく場所を固定するパターンです。

パフェパターンがわかりやすく、高い成功率を維持することができる地形です。

|a2_setup|

|a2_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@LhD8FeF8DeF8JeAgH -p *!

  # パフェ成功率
  success = 95.00% (4788/5040)
  * -> 95.00 %
  ∟ T -> 100.00 %
  ∟ I -> 95.00 %
  ∟ L -> 97.50 %
  ∟ J -> 97.50 %
  ∟ S -> 89.17 %
  ∟ Z -> 89.17 %
  ∟ O -> 96.67 %

----

パターンB'
===========================================

.. |b2_fig01| image:: img/b2/fig_001.png
   :scale: 50
.. |b2_fig02| image:: img/b2/fig_002.png
   :scale: 50
.. |b2_fig03| image:: img/b2/fig_003.png
   :scale: 50
.. |b2_fig04| image:: img/b2/fig_004.png
   :scale: 50
.. |b2_fig05| image:: img/b2/fig_005.png
   :scale: 50
.. |b2_fig06| image:: img/b2/fig_006.png
   :scale: 50
.. |b2_note| image:: img/b2/fig_note.png
   :scale: 50

.. |b2_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@JhglBeQ4DeRpglBtR4CeRphlBtQ4MeAgHRhRaHehWR?aPeAAAJhAtGexhAthlEehlBexSNeAAAJhgHAeAtwDAeg0Be?xSgHhWBeg0RpxSQaQph0Qag0RpJeAAAZhRpFeRLhWJeAAAO?hAPGeRLAPxSDehHBehlJeAAA" target="_blank">
     セットアップ：テト譜
   </a>

.. |b2_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@JhA8BeA8DeG8CeG8MeAgWYAlfT6BY0DfEToXOBlvs2?AUDEfETo/AC9gRpBtzhh0RpAeBtAehlg0wwGeglxwGeglg0?wwJeAAtNBse88AwXHDBQOHSA1dEEBBYHDBwveRA1dkRBDYH?DBwicRASoDfETo3ABlvs2A2HEfEVZi9AFbcRA1d0KB3XnQB?YDDSA1AlVBhAAAASgwwhlGexwglGewwR4GeR4glNeywAeBP?FeAtRawSGeQaIeRawSJeAAtGBlvs2AVGEfETY+2Bl/m9BFw?DfE112KBlvs2AWJ88AwXHDBwPjRA1d0KBlrDfETYp6Alvs2?AiJEfET4d3Blvs2AGdAAA" target="_blank">
      消しかた：テト譜
   </a>

.. container:: field_images

  |b2_fig01|
  |b2_fig02|
  |b2_fig03|
  |b2_fig04|
  |b2_fig05|
  |b2_fig06|

|

O と [SZ] のおく場所を固定するパターンです。

ここでまとめた地形の中で最もパフェ成功率が低いですが、
パフェパターンが3パターンに集約可能なうえ、
パフェできない場合でもSTSDやT-Spin Double-Tripleが狙えるので展開しやすい地形です。

Tがはやいとパフェしやすい（先頭の場合は100%）のため、
Tがはやいときはパフェ、遅いときはT-Spinで割り切るのもひとつの戦略としてありです。

|b2_setup|

|b2_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@JhA8BeA8DeG8CeG8MeAgH -p *!

  # パフェ成功率  # 右側あけ
  success = 80.00% (4032/5040)
  * -> 80.00 %
  ∟ T -> 100.00 %
  ∟ I -> 75.00 %
  ∟ L -> 75.00 %
  ∟ J -> 75.00 %
  ∟ S -> 75.00 %
  ∟ Z -> 80.00 %
  ∟ O -> 80.00 %

.. note ::
  |b2_note|

  Oの位置を変えることで STMB Cave などのドネイトも狙えるようになる。

----

パターンC'
===========================================

.. |c2_fig01| image:: img/c2/fig_001.png
   :scale: 50
.. |c2_fig02| image:: img/c2/fig_002.png
   :scale: 50
.. |c2_fig03| image:: img/c2/fig_003.png
   :scale: 50
.. |c2_fig04| image:: img/c2/fig_004.png
   :scale: 50

.. |c2_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@HhglBeQ4FeglBtR4g0DehlBtQ4i0LeAgHKhQaIeRaI?egHSLLeAAAHhgWBegHBeAtBeg0gWBPgHAPgWAtR4g0jWwhQ?pj0JeAAANhgWHehWEeSawSNeAAA" target="_blank">
     セットアップ：テト譜
   </a>

.. |c2_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@HhA8BeA8FeF8DeH8LeAgWYAlfT6BY0DfEToXOBlvs2?AUDEfETo/ACZfBti0BeQ4BeA8BtA8g0BeR4AeF8zhH8Q4Ke?Bti0DewhA8BtA8g0BewwAewhF8ywwhH8AewhJeBti0Q4EeB?tAeg0R4ilFeQ4glVeAAt9AzXHDBQGfRA1dUzBGYHDBQpHSA?1d0ACzXHDBQRsRA1jB0ByXnQBm0nRA1d0KB3XHDBQeJSA1d?kRBiAAAA" target="_blank">
      消しかた：テト譜
   </a>

.. container:: field_images

  |c2_fig01|
  |c2_fig02|
  |c2_fig03|
  |c2_fig04|

|

[SZ] と [JL] のおく場所を固定するパターンです。

パフェパターンを3パターンで網羅できるのが特徴。

LJSZで組むとき、余裕があればネクストをみながら固定するミノを決めることで、パフェ成功率をあげることができる。

|c2_setup|

|c2_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@HhA8BeA8FeF8DeH8LeAgH -p *!

  # パフェ成功率  # 右側あけ
  success = 93.33% (4704/5040)
  * -> 93.33 %
  ∟ T -> 88.06 %
  ∟ I -> 100.00 %
  ∟ L -> 85.28 %
  ∟ J -> 95.28 %
  ∟ S -> 89.44 %
  ∟ Z -> 95.28 %
  ∟ O -> 100.00 %

----

パターンD'
===========================================

.. |d2_fig01| image:: img/d2/fig_001.png
   :scale: 50
.. |d2_fig02| image:: img/d2/fig_002.png
   :scale: 50
.. |d2_fig03| image:: img/d2/fig_003.png
   :scale: 50
.. |d2_fig04| image:: img/d2/fig_004.png
   :scale: 50
.. |d2_fig05| image:: img/d2/fig_005.png
   :scale: 50
.. |d2_fig06| image:: img/d2/fig_006.png
   :scale: 50
.. |d2_fig07| image:: img/d2/fig_007.png
   :scale: 50
.. |d2_fig08| image:: img/d2/fig_008.png
   :scale: 50
.. |d2_fig09| image:: img/d2/fig_009.png
   :scale: 50
.. |d2_fig10| image:: img/d2/fig_010.png
   :scale: 50

.. |d2_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@9gwhIewhBeR4Eewhg0R4RpDewhi0RpNeAgH9gwhIew?hIewhAPIeSLPeAAA9gQaIeQaBeQLFeQawhAPQLBtEehlwhQ?aAtNeAAAKhglwSHeAtxSGeBtQaNeAAA9gQaAeglGeQaAegl?GeglAeQaAPFeglAegWSLNeAAA/ggWFewhBegWBPBtBewhxS?hWRaBtglwhxSRaklwhJeAAAGhwwIewwHeAtwwFeSaKeAAAG?hQLFeglBeQLDexhglQawSQLDewhQpwwhlKeAAAMhQpwhGeR?pAPGegWBPMeAAAEhg0AeQaGeg0AeQaFeAtQpAeglDeSagWA?eglJeAAA" target="_blank">
     セットアップ：テト譜
   </a>

.. |d2_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@9gA8IeA8BeB8EeF8DeF8NeAgWYAlfT6BY0DfEToXOB?lvs2AUDEfETo/ACneA8RpFewwA8RpB8hlAexwF8glBtwwF8?glAeBtJeA8RpGeA8RpB8CeQ4AeF8BtR4F8AeBtQ4JeA8RpG?eA8RpB8AewwCeF8xwR4F8wwR4LeRpHeRpFewwFeBtxwGeBt?wwJeAAtCBlvs2A1sDfET4p9B0XHDBQhlRA1dEEBDY3JBXJD?SAVSk9ADHrRBRrDfET4UBBlvV6BirDfEX5uHBP0nRAyfAAA?neAAxSFeQLAAxSBAhWAeRLFAgWBPQLFAgWAeBPJeAAxSGeA?AxSBACewDAeFABPxDFAAeBPwDRewwwhFeQLxwwhFeRagWgH?FeQLxSwhSewwGeAtwwIehlFeAtRpKeAAtnBl/+AC11DfEYk?JIBlvs2A0EEfETYd9Alvs2A4EEfETI02Al/PVB5BEfETYtR?Blvs2AWxDfETYFwBlvs2AUGEfETo/AClvs2AUuDfETYp6Al?vs2AiJEfET4d3Blvs2AGtmAAneA8RpCewwhlwhA8RpB8Aex?wglwhF8BtglwhF8wwBtwhJeA8Rpi0wwBtAeA8RpB8g0xwBt?F8wwCeF8zhPeQ4AeQLAtFeQ4glAeAtFehWwSAtFeglQpAPQ?aKexSFeQaAexSBexwwhRaFewhglRaFeAPwDwSwhJeAAtnBl?/+AC11DfEYkJIBlvs2A0EEfETYd9Alvs2A4EEfETI02Al/P?VB5BEfETYtRBlvs2AWxDfETYFwBlvs2AUGEfETo/AClvs2A?UuDfETYp6Alvs2AiJEfET4d3Blvs2AG9oAA" target="_blank">
      消しかた：テト譜
   </a>

.. container:: field_images

  |d2_fig01|
  |d2_fig02|
  |d2_fig03|
  |d2_fig04|
  |d2_fig05|
  |d2_fig06|
  |d2_fig07|
  |d2_fig08|
  |d2_fig09|
  |d2_fig10|

|

O と [JL] のおく場所を固定するパターンです。

ツモが I O [SZ] [JL] の組み合わせだった場合は柔軟に組め、
余裕があれば、ネクストをみてから LJ のどちらを固定するか決めることができる。

もし、ふたつめのJSが早い場合は OJのスペース をあけ、LZが早い場合は OLのスペース をあけておくと良いです。

パフェパターンはTが遅いとき、複雑になりやすい傾向があるため、
そのときはSZを立てたり引っ掛けたりして、T-Spinに切り替えてしまうのもひとつの手です。

|d2_setup|

|d2_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@/gA8IeC8EeF8DeF8NeAgH -p *!

  # パフェ成功率  # OJを固定した地形
  success = 88.06% (4438/5040)
  * -> 88.06 %
  ∟ T -> 92.50 %
  ∟ I -> 81.53 %
  ∟ L -> 82.92 %
  ∟ J -> 85.00 %
  ∟ S -> 94.44 %
  ∟ Z -> 88.33 %
  ∟ O -> 91.67 %

----

パターンE'
===========================================

.. |e2_fig01| image:: img/e2/fig_001.png
   :scale: 50
.. |e2_fig02| image:: img/e2/fig_002.png
   :scale: 50
.. |e2_fig03| image:: img/e2/fig_003.png
   :scale: 50
.. |e2_fig04| image:: img/e2/fig_004.png
   :scale: 50

.. |e2_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@KhAtFeRpBtR4DeRpAtR4zhKeAgHKhgWFeQpQahWFeR?pglQeAAAKhgWBeQ4CegHiWxSR4RpgHRLhHRpg0glQpJeAAA?NhQaIeRaQpQaGeQLRaJeAAA" target="_blank">
     セットアップ：テト譜
   </a>

.. |e2_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@KhA8FeF8DeI8KeAgWYAlfT6BY0DfEToXOBlvs2AUDE?fETo/ACLgg0zhBeAtBei0A8BeBtwwAeF8AtywI8KeRpilBe?Atg0AeRpglCeBtg0GeAth0UeAAPrAaoo2Alvs2A0E88AwXH?DBQBOSA1dkRB0XHDBQelRA1d0KB4XHDBQeRBAZfRpilBei0?RpglA8zhQ4g0F8BeR4I8Q4Jeg0zhR4DexwQ4g0Q4QpQaklA?eB8RaQLglIeglOewwAeAPgHwhDexwwhQpxhFeQpwhgHwhIe?whJeAAtrAaoo2Alvs2A0E88AwXHDBQuCSA1dcHBEYHDBQel?RA1d0KB4XHDBQeRBA" target="_blank">
      消しかた：テト譜
   </a>

.. container:: field_images

  |e2_fig01|
  |e2_fig02|
  |e2_fig03|
  |e2_fig04|

|

O と [JL] のおく場所を固定するパターンです。

IOSZでよく使う地形で、そのときはネクストをみてから地形を決めることができます。

もしふたつめの Z がはやければ右端あけ、S がはやければ左端あけにすると良いです。

それによってある程度パターンを絞りやすくなり、パフェできないときは端開けRENに切り替えられます。

|e2_setup|

|e2_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@KhA8FeF8DeI8KeAgH -p *!

  # パフェ成功率  # 右端あけ
  success = 87.50% (4410/5040)
  * -> 87.50 %
  ∟ T -> 85.56 %
  ∟ I -> 86.67 %
  ∟ L -> 86.39 %
  ∟ J -> 89.17 %
  ∟ S -> 82.50 %
  ∟ Z -> 94.72 %
  ∟ O -> 87.50 %

----

おまけ
===========================================

ここから先はおまけなので、覚える必要はありません。

パフェ成功率を重視したい方は、参考にしてください。

パターンB'：パフェ重視
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. |b2p_fig01| image:: img/b2p/fig_001.png
   :scale: 50
.. |b2p_fig02| image:: img/b2p/fig_002.png
   :scale: 50
.. |b2p_fig03| image:: img/b2p/fig_003.png
   :scale: 50
.. |b2p_fig04| image:: img/b2p/fig_004.png
   :scale: 50
.. |b2p_fig05| image:: img/b2p/fig_005.png
   :scale: 50
.. |b2p_fig06| image:: img/b2p/fig_006.png
   :scale: 50

.. |b2p_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@/gQ4IeR4FeRpg0Q4BtDeRpi0BtMeAgH/ggHIegHQLH?eRLHeQLBPOeAAA/gg0Ieg0wwFeRawhwwFeQagWAeRaOeAAA?/gwDDeAtDexDBeBtBeiWwDRpAtglRpgWRah0hWglRpJeAAA?YhAtRpEeSagWQpJeAAAEhwSHeglwSHeglQLxSEexwAeglwS?JeAAAa" target="_blank">
      セットアップ：テト譜
   </a>

.. |b2p_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@/gA8IeB8FeF8DeG8MeAgWYAlfT6BY0DfEToXOBlvs2?AUDEfETo/ACneRpA8GeRpB8EeglF8zhG8ilJeRpA8GeRpB8?AeBtCeF8BtR4G8R4KeRpA8GeRpB8BeQ4AewwAeF8R4xwG8Q?4wwKeRpCehlwhBeRpDeglwhAewwFeglwhxwGewhAewwJeAA?tAAqeBtIeBtilQpFewhQaBtGehWQpMeBtIeAtAewSyhFeBP?wDQLGeRLglSewhFewDAeQLwhFeRawhAPGewDxhOehWAtFeh?0BtwwQLFeBthlGeg0Q4QLJeAAe" target="_blank">
       消しかた：テト譜
   </a>

.. container:: field_images

  |b2p_fig01|
  |b2p_fig02|
  |b2p_fig03|
  |b2p_fig04|

|

パターンB\\'のパフェ重視の地形です。

パターンB\\'のパフェ率80%が気になる場合は、この地形で代用できます。

パフェパターンの絞り込みが他地形と比較して少し難しいです。

|b2p_setup|

|b2p_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@/gA8IeB8FeF8DeG8MeAgH -p *!

  # パフェ成功率  # 右端あけ
  success = 91.03% (4588/5040)
  * -> 91.03 %
  ∟ T -> 95.00 %
  ∟ I -> 98.33 %
  ∟ L -> 82.78 %
  ∟ J -> 82.78 %
  ∟ S -> 93.33 %
  ∟ Z -> 92.78 %
  ∟ O -> 92.22 %

----

パターンE'：パフェ重視
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. |e2p_fig01| image:: img/e2p/fig_001.png
   :scale: 50
.. |e2p_fig02| image:: img/e2p/fig_002.png
   :scale: 50
.. |e2p_fig03| image:: img/e2p/fig_003.png
   :scale: 50
.. |e2p_fig04| image:: img/e2p/fig_004.png
   :scale: 50

.. |e2p_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@9gwhIewhCeAtEewhRpBtR4CewhRpAtR4NeAgHLhgWF?eQpQahWFeRpglPeAAA9gQaHewhQaCegWQ4CewhQagHgWhlB?eRpwhQaiHxSQ4RpwhJeAAAMhQaIeRaQpQaGeQLRaKeAAA" target="_blank">
       セットアップ：テト譜
   </a>

.. |e2p_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@9gA8IeA8CeA8EeG8CeF8NeAgWYAlfT6BY0DfEToXOB?lvs2AUDEfETo/AC+gg0zhEei0CeBtHewwBtFeywKeAAtSB0?n88AwXHDBQOHSASoDfET4BBClvs2AUuDfETYmzBlvs2AW0D?fETYN6BFbcRA1gJ+B2XnQBBYGPCJoo2Alvs2A2yDfEXElwB?lPhzB5xAAA+gwSglyhEexSAPCeBPHeQLBPFeSLKeAAtEBlv?s2AVGEfETY+2Bl/m9BFwDfE112KBlvs2AWJ88AwX3JBEYqR?A1zC+BGHcSASoDfET4ZOBlv1RBCCEfEVDRwBneF8CewhE8C?eAtwhG8BtwhF8AeAtAewhJeF8DeE8EeG8ywF8BewwKeF8De?E8EeG8i0F8Ceg0Kexwi0CewhAexwg0CeQ4AewhGeR4whHeQ?4whJeAAtbBlfjzBypDfET4p9BlPBBCWrDfET4ZOByXHDBwH?xRA1d8vB0XHDBQpjRA1Dq9BFYHDBwFhRAViRSB4XHDBwvwR?A1d0KBFYHDBQOHSA1QEBCBYPNBXLPBAneFACeQaEACeAPQa?GABPQaFAAeAPAeQaJeFADeEAEeGASLFABeQLKeFADeEAEeG?AiHFACegHReAtwwGewSAtwwGewSQawwFexhgHKeAAtwAlvs?2AVGEfETY+2Bl/m9BFwDfE112KBlvs2AWJEfETo3ABlvs2A?2HEfEVZi9A" target="_blank">
        消しかた：テト譜
   </a>

.. container:: field_images

  |e2p_fig01|
  |e2p_fig02|
  |e2p_fig03|
  |e2p_fig04|

|

パターンE\\'のパフェ重視の地形で、IOSZの4ミノ開幕で最高パフェ率を保持できる地形です。

パフェパターンもそれほど多くありません。

横に凸があるので、パフェ以外には展開が少ししにくいです。

|e2p_setup|

|e2p_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@/gA8IeB8FeF8DeG8MeAgH -p *!

  # パフェ成功率  # 右端あけ
  success = 93.97% (4736/5040)
  * -> 93.97 %
  ∟ T -> 100.00 %
  ∟ I -> 98.89 %
  ∟ L -> 93.06 %
  ∟ J -> 96.67 %
  ∟ S -> 89.44 %
  ∟ Z -> 86.67 %
  ∟ O -> 93.06 %
