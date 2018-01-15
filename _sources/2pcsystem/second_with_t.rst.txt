========================
パフェ2回目：Tあり
========================

**基本的に3地形でパフェ1回目テンプレの残りミノはカバーできます**

「TIOS = TIOZ」「OTSZ」はこの3地形で対応できませんが、
パフェ1回目にテンプレを使用した場合、このパターンは残りません。

グレースシステムを組む方は、個別で対応する必要あります（:ref:`addition_with_t` を参考にしてください）


対応表
===========================================

.. role:: strike

:strike:`取り消し線` は グレースシステム＆テンプレ で残らない組み合わせです

.. table::
   :widths: 10

   ============== === === ===
    TIO*           A   B   C
   ============== === === ===
    TIOL = TIOJ        O
    TIOS = TIOZ
   ============== === === ===

.. table::
   :widths: 10

   =============== === === ===
    IT**             A   B   C
   =============== === === ===
    :strike:`ITLJ`       O   O
    ITSZ
    ITLS = ITJZ      O   O   O
    ITLZ = ITJS      O   O   O
   =============== === === ===

.. table::
   :widths: 10

   =============== === === ===
    OT**            A   B   C
   =============== === === ===
    :strike:`OTLJ`
    OTSZ
    OTLS = OTJZ             O
    OTLZ = OTJS         O   O
   =============== === === ===

.. table::
   :widths: 10

   ======================= === === ===
    T***                    A   B   C
   ======================= === === ===
    :strike:`TLJS = TLJZ`       O
    TLSZ = TJSZ              O
   ======================= === === ===

.. note::

  基本地形は ふちさん にまとめていただきました。ありがとうございます。
  https://twitter.com/kitsune_fuchi

----

パターンA
===========================================

.. |a_fig01| image:: img/a/fig_001.png
   :scale: 50
.. |a_fig02| image:: img/a/fig_002.png
   :scale: 50
.. |a_fig03| image:: img/a/fig_003.png
   :scale: 50
.. |a_fig04| image:: img/a/fig_004.png
   :scale: 50
.. |a_fig05| image:: img/a/fig_005.png
   :scale: 50
.. |a_fig06| image:: img/a/fig_006.png
   :scale: 50
.. |a_fig07| image:: img/a/fig_007.png
   :scale: 50

.. |a_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@GhwwDeg0CexwDei0BtwwDezhBtJeAgHGhAPDeQaCew?hAPDeRawhQpglAPDeAth0wwglwSJeAAALhwSIewSAehWFew?SQLgWMeAAAPhQaFeRaAeQaGeQagWQaKeAAAGhQpDeQpCeQa?QpDeQpwhQpglQawhDeQpwwQpgWwSwhJeAAABhwwDeAPEeww?BeAPgWEeglAeQLgWEeglAegHSaJeAAABhglIehlCeQpDewh?AewSglRpDeRawwRpAtJeAAA" target="_blank">
     セットアップ：テト譜
   </a>

.. |a_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@BhA8IeB8CeA8DeF8DeF8JeAgWYAlfT6BY0DfEToXOB?lvs2AUDEfETo/ACneh0AtwhFeg0BtwhFeg0AtglwhFeilwh?PeQ4hlwhFeR4glwhFeg0Q4glwhFei0whPezhFehlh0FeglR?pg0AeywR4glRpg0BewwR4Kei0whAeBtywRpg0whBeBtwwAe?RpglwhFeilwhPeAAtSAlPZOBGCEfE2Cx2BlPBBCWbAAAneh?HAPQaFegHBPQaFegHAPgWQaFeiWQaPewSglwhglFeRawhgl?GewSglwhGeBPwhPeyhGeBtAeQLFeglwhQpQLGexhQLPexSR?eRaIeBtQeAAteAlvs2AFFEfETo69Alvs2ACqDfET4d3Blvs?2ACmAAA" target="_blank">
     消しかた：テト譜
   </a>

.. container:: field_images

  |a_fig01|
  |a_fig02|
  |a_fig03|
  |a_fig04|
  |a_fig05|
  |a_fig06|
  |a_fig07|

|

T と [SZ] のおく場所を固定するパターンです。

|a_setup|

|a_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@GhA8DeA8CeB8DeF8DeF8JeAgH -p *!

  # パフェ成功率
  success = 99.76% (5028/5040)
  * -> 99.76 %
  ∟ T -> 100.00 %
  ∟ I -> 100.00 %
  ∟ L -> 100.00 %
  ∟ J -> 100.00 %
  ∟ S -> 99.44 %
  ∟ Z -> 99.44 %
  ∟ O -> 99.44 %

----

パターンB
===========================================

.. |b_fig01| image:: img/b/fig_001.png
   :scale: 50
.. |b_fig02| image:: img/b/fig_002.png
   :scale: 50
.. |b_fig03| image:: img/b/fig_003.png
   :scale: 50
.. |b_fig04| image:: img/b/fig_004.png
   :scale: 50
.. |b_fig05| image:: img/b/fig_005.png
   :scale: 50
.. |b_fig06| image:: img/b/fig_006.png
   :scale: 50
.. |b_fig07| image:: img/b/fig_007.png
   :scale: 50
.. |b_fig08| image:: img/b/fig_008.png
   :scale: 50
.. |b_fig09| image:: img/b/fig_009.png
   :scale: 50
.. |b_fig10| image:: img/b/fig_010.png
   :scale: 50
.. |b_fig11| image:: img/b/fig_011.png
   :scale: 50
.. |b_fig12| image:: img/b/fig_012.png
   :scale: 50
.. |b_fig13| image:: img/b/fig_013.png
   :scale: 50
.. |b_fig14| image:: img/b/fig_014.png
   :scale: 50
.. |b_fig15| image:: img/b/fig_015.png
   :scale: 50

.. |b_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@Ghg0DeglAewwBeg0Deglywh0DehlzhJeAgHBhglDeg?HFeQLwwGewSBeQaEeRaBexwJeAAABhQpIeQpwwAewhAegHD?eQpwwglxhEeh0BeRLJeAAABhQLDewwDeRLglgHxwDewSRLh?WQaDehHBeRpJeAAAEhAtAeQLDewwAeglAtRLDeRpilwhDeA?tCewSglJeAAADhQ4APFeQLAeRpAewwDexSgWwhRaDewSDeQ?aJeAAABhQ4AewDGeR4wDgWAeQLDeAtwwQpgWAewSDeAtxwx?hwSJeAAABhwDDeAtDexDwwQLBtEegWBeQaUeAAABhwwDeAP?DexwQLg0BPDeQahlwhQawhDexhAeAtxhJeAAABhglIehlAe?QaFewhAegWQaFeRaAeQaLeAAABhwDBeAtFeQLwDAtQaFeAP?wSQaGeBPgWQaLeAAALhQpIeQpwhAewSFeQpAehWLeAAABhw?hBeAPFeAPglAPwhFeAPwSwhQpFeAPBeQpLeAAAMhQpAewhG?eQpAewhGeQpAtwhLeAAABhQaBewwFewwQLwwQaFewwxhQaG?eAPRLLeAAA" target="_blank">
     セットアップ：テト譜
   </a>

.. |b_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@BhA8IeA8BeA8AeA8DeF8DeF8JeAg0YAlfT6BY0DfET?oXOBlvs2AUDEfETo/ACneBtglwhFeilwhFeg0BtwhFei0wh?Pei0whFeilwhFeglR4whFeR4g0whPeh0AtwhFeg0BtwhFeg?0AtglwhFeilwhPeh0R4AeRpywg0R4glAeRpAewwAeg0ilFe?zhPeAAtAA" target="_blank">
     消しかた：テト譜
   </a>

.. container:: field_images

  |b_fig01|
  |b_fig02|
  |b_fig03|
  |b_fig04|
  |b_fig05|
  |b_fig06|
  |b_fig07|
  |b_fig08|
  |b_fig09|
  |b_fig10|
  |b_fig11|
  |b_fig12|
  |b_fig13|
  |b_fig14|
  |b_fig15|

|

T と O のおく場所を固定するパターンです。

|b_setup|

|b_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@BhA8IeA8BeA8AeA8DeF8DeF8JeAgH -p *!

  # パフェ成功率
  success = 97.14% (4896/5040)
  * -> 97.14 %
  ∟ T -> 98.33 %
  ∟ I -> 94.44 %
  ∟ L -> 100.00 %
  ∟ J -> 100.00 %
  ∟ S -> 94.44 %
  ∟ Z -> 94.44 %
  ∟ O -> 98.33 %

----

パターンC
===========================================

.. |c_fig01| image:: img/c/fig_001.png
   :scale: 50
.. |c_fig02| image:: img/c/fig_002.png
   :scale: 50
.. |c_fig03| image:: img/c/fig_003.png
   :scale: 50
.. |c_fig04| image:: img/c/fig_004.png
   :scale: 50
.. |c_fig05| image:: img/c/fig_005.png
   :scale: 50
.. |c_fig06| image:: img/c/fig_006.png
   :scale: 50
.. |c_fig07| image:: img/c/fig_007.png
   :scale: 50
.. |c_fig08| image:: img/c/fig_008.png
   :scale: 50

.. |c_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@Ohg0DeR4wwBei0AeR4ywzhJeAglZhxSFexwhlJeAAe?ThgWwSQaCeRpAehWAeRaRLhWJeAAeZhxSFexwhlJeAAeJhg?lDegHBehlwSBPR4QaxSwhCPRpRaglwSJeAAeWhgWwSQaFeh?WAeRaKeAAeRhxhCeglQpwhBehlxhhlAexhKeAAeWhgWwSQa?FehWAeRaKeAAe" target="_blank">
     セットアップ：テト譜
   </a>

.. |c_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@JhA8GeC8BeC8BeI8KeAgWYAlfT6BY0DfEToXOBlvs2?AUDEfETo/AC9gRpywBthlwhRpAewwR4BtglwhCeR4Ceglwh?IewhJeAAP7AToo2Alvs2A0E88AQe88AwXHDBQkuRA1dkRBB?YHDBQBOSA1dkRB0XHDBQelRA1d0KB4XHDBQeRBA9gRphlh0?R4wwwhRpA8glg0R4xwwhC8glg0C8wwwhI8whJeAAP7AUoo2?Alvs2A0E88Awc88AwXHDBQkuRA1dkRBBYHDBQBOSA1dkRB0?XHDBQelRA1d0KB4XHDBQeRBA" target="_blank">
     消しかた：テト譜
   </a>

.. container:: field_images

  |c_fig01|
  |c_fig02|
  |c_fig03|
  |c_fig04|
  |c_fig05|
  |c_fig06|
  |c_fig07|
  |c_fig08|

|

2つのパフェパターンを T と [SZ] のどちらが早いかによって使い分けるだけで、必ずパフェできるパターンです。

|c_setup|

|c_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@JhA8GeC8BeC8BeI8KeAgH -p *!

  # パフェ成功率
  success = 100.00% (5040/5040)
  * -> 100.00 %
  ∟ T -> 100.00 %
  ∟ I -> 100.00 %
  ∟ L -> 100.00 %
  ∟ J -> 100.00 %
  ∟ S -> 100.00 %
  ∟ Z -> 100.00 %
  ∟ O -> 100.00 %

----

.. _addition_with_t:

補足
===========================================

ITSZ
---------------------

.. |itsz_fig01| image:: img/itsz/fig_001.png
   :scale: 50
.. |itsz_fig02| image:: img/itsz/fig_002.png
   :scale: 50
.. |itsz_fig03| image:: img/itsz/fig_003.png
   :scale: 50
.. |itsz_fig04| image:: img/itsz/fig_004.png
   :scale: 50
.. |itsz_fig05| image:: img/itsz/fig_005.png
   :scale: 50
.. |itsz_fig06| image:: img/itsz/fig_006.png
   :scale: 50

.. |itsz_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@JhBtHewwBtR4DeywR4zhJeAgHJhglwhHeyhFexhQeA?AAKhwSIewSAehWFewSQLgWNeAAAJhgHgWBeR4DegHglQahl?wwBewhRLQaglQaCtQaJeAAANhgWQLGehWwSIexSKeAAANhw?hFexhAewhGewhglwhMeAAA" target="_blank">
     セットアップ：テト譜
   </a>

.. |itsz_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@JhB8HeE8DeI8JeAgHBgwhh0ywR4hlwhg0B8wwR4Rpg?lwhg0E8RpglwhI8Tewhh0Btywhlwhg0BeBtwwRpglwhg0Ee?RpglwhSeAAP7APoo2Alvs2A0E88AQS88AwXHDBQkuRA1dkR?BBYHDBQBOSA1dkRB0XHDBQelRA1d0KB4XHDBQeRBA9gwhh0?BtywR4whg0B8BtwwR4glwhg0E8ilwhI8JeAAP7AMoo2Alvs?2A0E88AwW88AwXHDBQkuRA1dkRBBYHDBQBOSA1dkRB0XHDB?QelRA1d0KB4XHDBQeRBA" target="_blank">
     消しかた：テト譜
   </a>

.. container:: field_images

  |itsz_fig01|
  |itsz_fig02|
  |itsz_fig03|
  |itsz_fig04|
  |itsz_fig05|
  |itsz_fig06|

|

2つのパフェパターンを O と [LJ] のどちらが早いかによって使い分けるだけで、必ずパフェできるパターンです。

|itsz_setup|

|itsz_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@JhB8HeE8DeI8JeAgH -p *!

  # パフェ成功率
  success = 100.00% (5040/5040)
  * -> 100.00 %
  ∟ T -> 100.00 %
  ∟ I -> 100.00 %
  ∟ L -> 100.00 %
  ∟ J -> 100.00 %
  ∟ S -> 100.00 %
  ∟ Z -> 100.00 %
  ∟ O -> 100.00 %

----

OTSZ
---------------------

.. |otsz_fig01| image:: img/otsz/fig_001.png
   :scale: 50
.. |otsz_fig02| image:: img/otsz/fig_002.png
   :scale: 50
.. |otsz_fig03| image:: img/otsz/fig_003.png
   :scale: 50
.. |otsz_fig04| image:: img/otsz/fig_004.png
   :scale: 50
.. |otsz_fig05| image:: img/otsz/fig_005.png
   :scale: 50
.. |otsz_fig06| image:: img/otsz/fig_006.png
   :scale: 50
.. |otsz_fig07| image:: img/otsz/fig_007.png
   :scale: 50
.. |otsz_fig08| image:: img/otsz/fig_008.png
   :scale: 50
.. |otsz_fig09| image:: img/otsz/fig_009.png
   :scale: 50
.. |otsz_fig10| image:: img/otsz/fig_010.png
   :scale: 50

.. |otsz_setup| raw:: html

   <a href="http://fumen.zui.jp/?v115@KhAtFeRpBtR4wwCeRpAtR4ywLeAgHKhwhHexhgWwSQ?aEewShHAPRaLeAAAKhwSFeQpQaxSFeRpwwCtNeAwhVhglQp?whFehlAexhLeAwhKhAtFeAPBeAtRaDeAPRLhHOeAwDNhwhG?ehWwhwwxhEeRpg0glwhJeAAANhgWFeglQpwhhWDehlAPxSg?HLeAAANhwhFegWwSQaxhQpQaBehWAtRpwhRaJeAAeUhglQp?whFehlAexhMeAAAUhgWQawhAeBPCehWAeBPRaKeAAA" target="_blank">
      セットアップ：テト譜
   </a>

.. |otsz_solution| raw:: html

   <a href="http://fumen.zui.jp/?v115@KhA8FeG8CeH8LeAgWYAlfT6BY0DfEToXOBlvs2AUDE?fETo/ACEhwwHeywHeBtIeBtJeAAtOBlvs2AWJEfETovRBlv?s2A4pDfET4hzBlvs2A1sDfETY+2Blvs2AZrDfEX2NEBlvs2?A4pDfETYmzBlvs2AUDEfEXElwBl/PwBY2AAA9gg0zhR4Aeh?li0AeR4CeglIeglTeAAtKBlvV6BUuDfETYO6Alvs2AYDEfE?T4xRBlvs2AUGEfEVGkLBlvNwBlJEfET4BBCFbUOCJoo2Alv?s2A2yDfEXElwBlPhzB5xAAA9gwSglyhxDQLhWxSAPAexDSL?gWGeBPgWHeBPJeAAtQBlvV6BUuDfETYO6Alvs2A2BEfETYN?EBlvs2AW0DfETYN6BlPR6BlxDfE3BkBClvs2AWJ88AwGcSA?SoDfET4ZOBlv1RBCCEfEVDRwB9gxwi0Eexwg0keAAtcBlvs?2A1sDfETo3ABlvs2AUDEfETYOVBlvs2A2HoRA1dE6BxXHDB?QTOSA1d0ACDYHDBQpTzAlPJ6AyBEfE1ZtRBlPp9BhxDfE5x?RSBlvs2AUuDfEZk0KBChR4ywDeR4Btwwg0GeBtg0Heh0JeA?AtsAlvs2AEqDfET4cBClvs2AGFEfET4dBBxno2Aqn88Awm7?8AQeEfEZYlHBChgWgHCPDehWwhglwhSehWJeAAtsAlvs2AE?qDfET4cBClvs2AGFEfET4dBByno2Aqn88Awm78AQeEfE2vr?VBChglg0ywDehlAPSLGexhQaHewhglJeAAtfAlvs2AEqDfE?T4cBClvs2AGFEfET4dBBzno2AUuzBAYhRawhHeQagWJeAAt?fAlvs2AEqDfET4cBClvs2AGFEfET4dBB0no2AauzBAQgwwB?tR4DeywBtg0GeR4g0Heh0OegWwSgWxhDehWAth0wwRehlJe?AAteAlvs2AEqDfET4cBClvs2AGFEfET4dBB1no2AqOBAA" target="_blank">
      消しかた：テト譜
   </a>

.. container:: field_images

  |otsz_fig01|
  |otsz_fig02|
  |otsz_fig03|
  |otsz_fig04|
  |otsz_fig05|
  |otsz_fig06|
  |otsz_fig07|
  |otsz_fig08|
  |otsz_fig09|
  |otsz_fig10|

|

最初に置いたOの上の2ラインの埋め方が JI (LI) と OL (OJ) があるので、他のTありパターンと比べると少し難しい。

基本的な考えは JI (LI) で組めるか確認して、できないときはOL (OJ)を入れます。

|otsz_setup|

|otsz_solution|

::

  java -jar sfinder.jar percent -fc 0 -td 1 -t v115@KhA8FeG8CeH8LeAgH -p *!

  # パフェ成功率
  success = 99.84% (5032/5040)
  * -> 99.84 %
  ∟ T -> 100.00 %
  ∟ I -> 99.72 %
  ∟ L -> 99.58 %
  ∟ J -> 100.00 %
  ∟ S -> 100.00 %
  ∟ Z -> 100.00 %
  ∟ O -> 99.58 %
