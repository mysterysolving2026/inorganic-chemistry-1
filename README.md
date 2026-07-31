<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>植物栄養学</title>
<style>
body {
    font-family: "Yu Gothic", sans-serif;
    margin: 30px;
    background: #f7f7f7;
}
h1 {
    text-align: center;
    color: #2a5c2a;
}
.question {
    background: #ffffff;
    padding: 15px;
    margin-bottom: 20px;
    border-left: 6px solid #2a5c2a;
    border-radius: 5px;
}
.answer {
    display: none;
    margin-top: 10px;
    padding: 10px;
    background: #e8f5e9;
    border-radius: 5px;
}
button {
    margin-top: 10px;
    padding: 8px 12px;
    background: #2a5c2a;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}
button:hover {
    background: #3b7a3b;
}
</style>

<script>
function toggleAnswer(id) {
    const ans = document.getElementById(id);
    ans.style.display = ans.style.display === "none" ? "block" : "none";
}
</script>
</head>

<body>

<h1>植物栄養学</h1>
<!-- Q1 -->
<div class="question">
    <p><b>1. ノーマン・ボーローグが行った1940〜1960年代の食料大量増産は何と呼ばれるか？</b></p>
    <button onclick="toggleAnswer('a1')">答えを見る</button>
    <div class="answer" id="a1">
        <p><b>正解：緑の革命</b></p>
        <p>高収量品種の開発と肥料・灌漑技術の普及により、世界の食料生産を大幅に増加させた農業革新。</p>
    </div>
</div>

<!-- Q2 -->
<div class="question">
    <p><b>2. 人類の食料生産割合のうち，イネが占める割合はどのくらいか？</b></p>
    <button onclick="toggleAnswer('a2')">答えを見る</button>
    <div class="answer" id="a2">
        <p><b>正解：22%</b></p>
        <p>イネは世界の食料生産の約22%を占め、特にアジアで主食として重要。</p>
    </div>
</div>

<!-- Q3 -->
<div class="question">
    <p><b>3. 日本の女性の20〜40%、妊婦の30%が罹患すると言われる貧血はどのミネラル不足で発生するか？</b></p>
    <button onclick="toggleAnswer('a3')">答えを見る</button>
    <div class="answer" id="a3">
        <p><b>正解：鉄</b></p>
        <p>鉄はヘモグロビンの構成要素であり、欠乏すると鉄欠乏性貧血が起こる。</p>
    </div>
</div>

<!-- Q4 -->
<div class="question">
    <p><b>4. 陸上での過剰な肥料散布により海洋の植物プランクトンが繁殖し、貧酸素水塊が形成されることで海底生物が死滅する現象を何と呼ぶか？</b></p>
    <button onclick="toggleAnswer('a4')">答えを見る</button>
    <div class="answer" id="a4">
        <p><b>正解：青潮</b></p>
        <p>青潮は、植物プランクトンの異常増殖後に貧酸素化が進み、海底付近の水が白濁し、生物が大量死する現象。赤潮とは異なり、酸素不足が主因となる。</p>
    </div>
</div>


<!-- Q5 -->
<div class="question">
    <p><b>5. OsNramp5という遺伝子の機能を失わせることで、イネはどの有害元素を蓄積しなくなるか？</b></p>
    <button onclick="toggleAnswer('a5')">答えを見る</button>
    <div class="answer" id="a5">
        <p><b>正解：カドミウム</b></p>
        <p>OsNramp5はカドミウム吸収に関わる輸送体であり、機能欠損によりカドミウム蓄積が抑制される。</p>
    </div>
</div>

<!-- Q6 -->
<div class="question">
    <p><b>6. 植物の無機栄養説の先駆者であり、最小養分律を提唱した人物は誰か？</b></p>
    <button onclick="toggleAnswer('a6')">答えを見る</button>
    <div class="answer" id="a6">
        <p><b>正解：Carl Philipp Sprengel</b></p>
        <p>Sprengelが最小養分律を提唱し、後にリービッヒが広めたことで広く知られるようになった。</p>
    </div>
</div>

<!-- Q7 -->
<div class="question">
    <p><b>7. リービッヒの三要素説に含まれない元素はどれか？</b></p>
    <button onclick="toggleAnswer('a7')">答えを見る</button>
    <div class="answer" id="a7">
        <p><b>正解：イオウ</b></p>
        <p>三要素説は窒素・リン・カリウムの3つであり、イオウは含まれない。</p>
    </div>
</div>

<!-- Q8 -->
<div class="question">
    <p><b>8. 次のうち、植物の必須元素に含まれないものはどれか？</b></p>
    <button onclick="toggleAnswer('a8')">答えを見る</button>
    <div class="answer" id="a8">
        <p><b>正解：ナトリウム</b></p>
        <p>ナトリウムは一部植物で有益だが、必須元素ではない。</p>
    </div>
</div>

<!-- Q9 -->
<div class="question">
    <p><b>9. 植物が鉄欠乏などにより葉緑素不足で葉が白色化する現象を何と呼ぶか？</b></p>
    <button onclick="toggleAnswer('a9')">答えを見る</button>
    <div class="answer" id="a9">
        <p><b>正解：chlorosis（クロロシス）</b></p>
        <p>クロロシスは葉緑素の不足により葉が黄化・白化する典型的な欠乏症状。</p>
    </div>
</div>

<!-- Q10 -->
<div class="question">
    <p><b>10. 必須元素欠乏のうち、全体の葉が暗緑色（下葉は紫色）となり、葉が小型になる特徴を示すのはどれか？</b></p>
    <button onclick="toggleAnswer('a10')">答えを見る</button>
    <div class="answer" id="a10">
        <p><b>正解：リン</b></p>
        <p>リン欠乏では葉が暗緑色化し、下葉が紫色を呈することが多く、葉の小型化も特徴。</p>
    </div>
</div>

</body>
</html>

<!-- Q11 -->
<div class="question">
    <p><b>11. 植物においてソースとは「　」が行われる場所，シンクとは「　」産物を利用･貯蔵する場所を指す。</b></p>
    <button onclick="toggleAnswer('a11')">答えを見る</button>
    <div class="answer" id="a11">
        <p><b>正解：光合成 ／ 光合成産物の利用・貯蔵</b></p>
        <p>ソースは主に成熟葉で、光合成により糖を生産する場所。シンクは成長点・根・果実などで、光合成産物を利用または蓄積する。</p>
    </div>
</div>

<!-- Q12 -->
<div class="question">
    <p><b>12. Figure5.5 の黒線で囲まれた部分（英語で cortex）のことをなんと呼ぶか？</b></p>
    <img src="C:\Users\kaho owner\OneDrive - 三重大学\3年\html作り\植物栄養学2.1.jpg" width="400">
    <button onclick="toggleAnswer('a12')">答えを見る</button>
    <div class="answer" id="a12">
        <p><b>正解：皮層</b></p>
        <p>皮層（cortex）は表皮と内皮の間にある組織で、根の物質移動や貯蔵に関わる。</p>
    </div>
</div>

<!-- Q13 -->
<div class="question">
    <p><b>13. 2枚目の写真はモデル植物（シロイヌナズナ）がどの元素の不足を感知した状態か？</b></p>
    <img src="C:\Users\kaho owner\OneDrive - 三重大学\3年\html作り\植物栄養学2.2.png" width="400">
    <button onclick="toggleAnswer('a13')">答えを見る</button>
    <div class="answer" id="a13">
        <p><b>正解：リン</b></p>
        <p>リン欠乏を感知すると根の形態や蛍光シグナルが特徴的に変化する。</p>
    </div>
</div>

<!-- Q14 -->
<div class="question">
    <p><b>14. 次の①と②に入る言葉の組み合わせで正しいものを選べ。</b></p>
    <button onclick="toggleAnswer('a14')">答えを見る</button>
    <div class="answer" id="a14">
        <p><b>正解：①硝酸　②オーキシン</b></p>
        <p>NRT1.1 は硝酸輸送体であると同時にオーキシンも輸送する。硝酸量によって側根形成が調節される。</p>
    </div>
</div>

<!-- Q15 -->
<div class="question">
    <p><b>15. 植物には二通りの水・養分の流れが存在する。①〜④の組み合わせで正しいものを選べ。植物には二通りの水･養分の流れが存在する。（①）プラストは細胞膜外と木部の導管を通る経路，（②）は細胞質の中と原形質連絡を通る経路である。（①）は（③）（②）は（④）をそれぞれ意味する接頭語である。
</b></p>
    <button onclick="toggleAnswer('a15')">答えを見る</button>
    <div class="answer" id="a15">
        <p><b>正解：①アポ　②シム　③離れて　④共同で</b></p>
        <p>アポプラストは細胞壁・導管など細胞膜外の経路（共同で＝apo）。シンプラストは細胞質と原形質連絡の経路（離れて＝sym）。</p>
    </div>
</div>

<!-- Q16 -->
<div class="question">
    <p><b>16. カスパリー線は①の流れを遮断し、内皮で②経路へ切り替えさせる構造。</b></p>
    <button onclick="toggleAnswer('a16')">答えを見る</button>
    <div class="answer" id="a16">
        <p><b>正解：①アポプラスト、②シンプラスト</b></p>
    </div>
</div>

<!-- Q17 -->
<div class="question">
    <p><b>17. 3つ目の図に相当するものを選択せよ。</b></p>
    <img src="C:\Users\kaho owner\OneDrive - 三重大学\3年\html作り\植物栄養学2.3.png" width="400">
    <button onclick="toggleAnswer('a17')">答えを見る</button>
    <div class="answer" id="a17">
        <p><b>正解：導管要素</b></p>
        <p>図は perforation plate を持つ典型的な導管要素（xylem vessel element）。水輸送に特化した細胞。</p>
    </div>
</div>

<!-- Q18 -->
<div class="question">
    <p><b>18. ミュンヒの圧流説について①〜④の組み合わせで正しいものを選べ。師管液は葉などの（①）組織から成長点や子実，根などの（②）組織へと流れる。これは浸透圧の違いによって（①）組織に多い（③）が少ない（②）組織へと水と共に押し出されるためである。</b></p>
    <button onclick="toggleAnswer('a18')">答えを見る</button>
    <div class="answer" id="a18">
        <p><b>正解：①ソース　②シンク　③糖</b></p>
        <p>ソース（成熟葉）で糖濃度が高まり浸透圧が上昇し、師管液がシンクへ押し出される。</p>
    </div>
</div>

<!-- Q19 -->
<div class="question">
    <p><b>19. イネ節の横断面の自家蛍光像で、葉への養分供給や維管束間輸送を担う特殊化された維管束はどれか？</b></p>
    <img src="C:\Users\kaho owner\OneDrive - 三重大学\3年\html作り\植物栄養学2.4.png" width="400">
    <button onclick="toggleAnswer('a19')">答えを見る</button>
    <div class="answer" id="a19">
        <p><b>正解：肥大維管束</b></p>
    </div>
</div>

<!-- Q20 -->
<div class="question">
    <p><b>20. 有害なカドミウムが種子（穂）に輸送されないように、イネではカドミウムをある元素と結合させて肥大維管束に留めている。その元素はどれか？</b></p>
    <button onclick="toggleAnswer('a20')">答えを見る</button>
    <div class="answer" id="a20">
        <p><b>正解：イオウ</b></p>
        <p>イネはカドミウムを硫黄（S）と結合させ、フィトケラチンなどの形で肥大維管束に隔離する。</p>
    </div>
</div>

<!-- Q21 -->
<div class="question">
    <p><b>21. 次の説明に相当する葉の組織を選択せよ。  
    輻射熱で水分を蒸散し輸送エネルギーを発生できるよう，また酸素と二酸化炭素を交換できるように空間が空いている。</b></p>
    <button onclick="toggleAnswer('a21')">答えを見る</button>
    <div class="answer" id="a21">
        <p><b>正解：海綿状組織</b></p>
        <p>海綿状組織は細胞間隙が大きく、ガス交換や蒸散に適した構造を持つ。</p>
    </div>
</div>

<!-- Q22 -->
<div class="question">
    <p><b>22. 気孔を開くために必要なフォトトロピンは何色の光に反応するか？</b></p>
    <button onclick="toggleAnswer('a22')">答えを見る</button>
    <div class="answer" id="a22">
        <p><b>正解：青</b></p>
        <p>フォトトロピンは青色光受容体で、気孔開口や葉の傾き調節に関わる。</p>
    </div>
</div>

<!-- Q23 -->
<div class="question">
    <p><b>23. 気孔を閉じるのに重要な植物ホルモンはどれか？</b></p>
    <button onclick="toggleAnswer('a23')">答えを見る</button>
    <div class="answer" id="a23">
        <p><b>正解：アブシジン酸</b></p>
        <p>アブシジン酸（ABA）は乾燥ストレス時に気孔を閉じる働きを持つ。</p>
    </div>
</div>

<!-- Q24 -->
<div class="question">
    <p><b>24. アクアポリンは①のほうが、②より種類が多い</b></p>
    <button onclick="toggleAnswer('a24')">答えを見る</button>
    <div class="answer" id="a24">
        <p><b>正解：①植物　②哺乳類</b></p>
        <p>以下は正しい文章：[1]乾燥時に根の細胞に水を供給することで，地上部への水流圧を作り出す
        [2]中心部分でろうと状の構造をとり，水より大きな分子を通さない
        [3]液胞に蓄積する水の量を調整する</p>
    </div>
</div>

<!-- Q25 -->
<div class="question">
    <p><b>25. 酸素の発見者と言われる人物は誰か？</b></p>
    <button onclick="toggleAnswer('a25')">答えを見る</button>
    <div class="answer" id="a25">
        <p><b>正解：Joseph Priestley</b></p>
        <p>プリーストリーは1774年に酸素を発見したとされる化学者。</p>
    </div>
</div>

<!-- Q26 -->
<div class="question">
    <p><b>26. 大気中の二酸化炭素濃度が最も高くなる条件はどれか？</b></p>
    <button onclick="toggleAnswer('a26')">答えを見る</button>
    <div class="answer" id="a26">
        <p><b>正解：北極近辺の冬から春にかけて</b></p>
        <p>冬季は植物の光合成量が低下し、CO₂が大気中に蓄積しやすい。</p>
    </div>
</div>

<!-- Q27 -->
<div class="question">
    <p><b>27. 緑色植物の光合成に有効な波長（光合成有効放射）の範囲を選択せよ。</b></p>
    <button onclick="toggleAnswer('a27')">答えを見る</button>
    <div class="answer" id="a27">
        <p><b>正解：400〜700nm</b></p>
        <p>この範囲は可視光域で、光合成に利用される主要な波長である。</p>
    </div>
</div>

<!-- Q28 -->
<div class="question">
    <p><b>28. 光合成によって糖などに固定されるエネルギー量（年間）は、地球が太陽から受ける全光エネルギーのどのくらいか？</b></p>
    <button onclick="toggleAnswer('a28')">答えを見る</button>
    <div class="answer" id="a28">
        <p><b>正解：0.1%未満</b></p>
        <p>光合成のエネルギー固定効率は非常に低く、全受光量の0.1%未満とされる。</p>
    </div>
</div>

<!-- Q29 -->
<div class="question">
    <p><b>29. 光合成では（ア）膜上の光化学系IおよびIIでATPとNADPHが生産される。この反応は以前（イ）反応と呼ばれていたが、現在は使われない。正しい組み合わせはどれか？</b></p>
    <button onclick="toggleAnswer('a29')">答えを見る</button>
    <div class="answer" id="a29">
        <p><b>正解：（ア）チラコイド（イ）明</b></p>
        <p>光化学反応はチラコイド膜で起こり、かつて「明反応」と呼ばれていた。</p>
    </div>
</div>

<!-- Q30 -->
<div class="question">
    <p><b>30. 植物が光合成を行う際に放出する酸素(O₂)はどれを起源としているか？</b></p>
    <button onclick="toggleAnswer('a30')">答えを見る</button>
    <div class="answer" id="a30">
        <p><b>正解：水（H₂O）</b></p>
        <p>光化学系IIで水が分解され、その際に発生した酸素が大気中へ放出される。</p>
    </div>
</div>

<!-- Q31 -->
<div class="question">
    <p><b>31. 光化学系IIにおいて、水の解離と酸素発生に寄与する金属元素はどれか？</b></p>
    <button onclick="toggleAnswer('a31')">答えを見る</button>
    <div class="answer" id="a31">
        <p><b>正解：マンガン</b></p>
        <p>光化学系IIのマンガンクラスター（Mn₄CaO₅）が水分解反応を担い、酸素発生に必須である。</p>
    </div>
</div>

<!-- Q32 -->
<div class="question">
    <p><b>32. 次の（ア）（イ）の組み合わせで正しいものを選べ。</b></p>
    <button onclick="toggleAnswer('a32')">答えを見る</button>
    <div class="answer" id="a32">
        <p><b>正解：ア：ビリン　イ：還元</b></p>
        <p>フィコエリスリンはビリン系色素。光エネルギーはCO₂を還元して糖を作るためのNADPH生成に使われる。</p>
    </div>
</div>

<!-- Q33 -->
<div class="question">
    <p><b>33. 光化学系においてATP合成酵素がATPを1分子合成するために必要な水素イオン数はいくつか？</b></p>
    <button onclick="toggleAnswer('a33')">答えを見る</button>
    <div class="answer" id="a33">
        <p><b>正解：4</b></p>
        <p>ATP合成酵素は約4個のH+の流入でADPをリン酸化しATPを合成する。ミトコンドリアでは3個のH+の流入。</p>
    </div>
</div>

<!-- Q34 -->
<div class="question">
    <p><b>34. Melvin Calvinが光合成研究で受賞したノーベル賞はどれか？</b></p>
    <button onclick="toggleAnswer('a34')">答えを見る</button>
    <div class="answer" id="a34">
        <p><b>正解：化学賞</b></p>
        <p>カルビンは炭素固定経路（カルビン回路）の解明により1961年ノーベル化学賞を受賞した。</p>
    </div>
</div>

<!-- Q35 -->
<div class="question">
    <p><b>35. Rubiscoがカルボキシラーゼとして機能した場合の正しい組み合わせはどれか？付加するのは①、反応生成物は②のみ</b></p>
    <button onclick="toggleAnswer('a35')">答えを見る</button>
    <div class="answer" id="a35">
        <p><b>正解：付加するのは①二酸化炭素，反応生成物は②3-ホスホグリセリン酸のみ</b></p>
        <p>カルボキシラーゼ反応ではCO₂が付加され、2分子の3-PGAが生成する。</p>
    </div>
</div>

<!-- Q36 -->
<div class="question">
    <p><b>36. 次の（ア）（イ）の組み合わせで正しいものを選べ。植物が強い光を受けエネルギー供給が過剰になると，酸素から活性酸素が発生し，細胞の活動に障害が発生することで（ア）が誘導される。植物はフォトトロピンで強い光を感知すると，葉緑体はそれを回避するように細胞の（イ）側に回避する行動を取る。
</b></p>
    <button onclick="toggleAnswer('a36')">答えを見る</button>
    <div class="answer" id="a36">
        <p><b>正解：ア：アポトーシス　イ：細胞側面</b></p>
        <p>過剰光で活性酸素が蓄積するとアポトーシスが誘導される。強光回避のため葉緑体は細胞側面へ移動する。</p>
    </div>
</div>

<!-- Q37 -->
<div class="question">
    <p><b>37. C4植物とCAM植物の正しい組み合わせはどれか？</b></p>
    <button onclick="toggleAnswer('a37')">答えを見る</button>
    <div class="answer" id="a37">
        <p><b>正解：C4植物：サトウキビ，CAM植物：アロエ</b></p>
        <p>サトウキビは典型的C4植物、アロエは夜間にCO₂固定するCAM植物である。</p>
    </div>
</div>

<!-- Q38 -->
<div class="question">
    <p><b>38. C4光合成に関する（ア）（イ）の正しい組み合わせはどれか？</b></p>
    <button onclick="toggleAnswer('a38')">答えを見る</button>
    <div class="answer" id="a38">
        <p><b>正解：ア：葉肉細胞　イ：3-ホスホグリセリン酸</b></p>
        <p>C4植物は葉肉細胞でCO₂を濃縮し、維管束鞘細胞で再放出して3-PGAとして固定する。</p>
    </div>
</div>

<!-- Q39 -->
<div class="question">
    <p><b>39. C4植物が高い成長率を持つ理由の正しい組み合わせはどれか？</b></p>
    <button onclick="toggleAnswer('a39')">答えを見る</button>
    <div class="answer" id="a39">
        <p><b>正解：ア：Rubisco　イ：チッ素</b></p>
        <p>CO₂濃縮によりRubisco量を少なくでき、その分の窒素を他のタンパク質合成に回せるため成長が速い。</p>
    </div>
</div>

<!-- Q40 -->
<div class="question">
    <p><b>40. CAM光合成に関する（ア）（イ）の正しい組み合わせはどれか？CAM植物は（ア）に気孔を開いて二酸化炭素を取り込み，リンゴ酸として（イ）に貯蔵する。</b></p>
    <button onclick="toggleAnswer('a40')">答えを見る</button>
    <div class="answer" id="a40">
        <p><b>正解：ア：夜　イ：液胞</b></p>
        <p>CAM植物は夜に気孔を開きCO₂を取り込み、リンゴ酸として液胞に蓄える。</p>
    </div>
</div>

<!-- Q41 -->
<div class="question">
    <p><b>41. 膜輸送タンパク質が持つ特徴として膜貫通領域は①構造を取る。。</b></p>
    <button onclick="toggleAnswer('a41')">答えを見る</button>
    <div class="answer" id="a41">
        <p><b>正解：①αヘリックス構造</b></p>
        <p>膜貫通領域は一般に疎水性アミノ酸からなるαヘリックス構造を取る。βシートはバレル構造など特殊な場合のみ。</p>
        <p>以下は正解：[1]膜貫通領域は20アミノ酸程度の長さである。[2]物質輸送のための通路を持つ。[3]疎水アミノ酸が多い。
    </div>
</div>

<!-- Q42 -->
<div class="question">
    <p><b>42. 次の中で疎水性の芳香族アミノ酸を選択せよ。</b></p>
    <button onclick="toggleAnswer('a42')">答えを見る</button>
    <div class="answer" id="a42">
        <p><b>正解：フェニルアラニン</b></p>
        <p>フェニルアラニンは芳香族で疎水性。チロシンは芳香族だが極性側鎖を持つ。</p>
    </div>
</div>

<!-- Q43 -->
<div class="question">
    <p><b>43. Ca²⁺が100倍の濃度差を持つとき、ネルンスト式で求まる平衡電位はいくつか？</b></p>
    <button onclick="toggleAnswer('a43')">答えを見る</button>
    <div class="answer" id="a43">
        <p><b>正解：59mV</b></p>
        <p>ネルンスト式 E = (RT/zF) ln([外]/[内]) より、z=2 だが、Ca²⁺は2価のイオンなので 59mV×2/2＝59mVとなる。</p>
    </div>
</div>

<!-- Q44 -->
<div class="question">
    <p><b>44. 細胞質における濃度が細胞外より非常に低いものを選べ。</b></p>
    <button onclick="toggleAnswer('a44')">答えを見る</button>
    <div class="answer" id="a44">
        <p><b>正解：カルシウムイオン</b></p>
        <p>Ca²⁺は細胞質では極めて低濃度に保たれ、シグナルとして利用される。</p>
    </div>
</div>

<!-- Q45 -->
<div class="question">
    <p><b>45. 植物細胞で最もpHが高いのはどれか？</b></p>
    <button onclick="toggleAnswer('a45')">答えを見る</button>
    <div class="answer" id="a45">
        <p><b>正解：細胞質</b></p>
        <p>細胞外はpH=5、細胞質はpH=7.4、液胞はpH=5.0。</p>
    </div>
</div>

<!-- Q46 -->
<div class="question">
    <p><b>46. 受動輸送を行う膜輸送タンパク質はどれか？</b></p>
    <button onclick="toggleAnswer('a46')">答えを見る</button>
    <div class="answer" id="a46">
        <p><b>正解：チャネル</b></p>
        <p>チャネルは濃度勾配に従う受動輸送。ポンプやABCは能動輸送。</p>
    </div>
</div>

<!-- Q47 -->
<div class="question">
    <p><b>47. プロトンポンプのうち、植物の（ア）に見られるものは（イ）型と呼ばれる。正しい組み合わせは？</b></p>
    <button onclick="toggleAnswer('a47')">答えを見る</button>
    <div class="answer" id="a47">
        <p><b>正解：（ア）液胞膜　（イ）V型</b></p>
        <p>液胞膜にはV型ATPaseが存在し、液胞内を強酸性に保つ。</p>
    </div>
</div>

<!-- Q48 -->
<div class="question">
    <p><b>48. 立体構造の変化によって物質を輸送するものはどれか？</b></p>
    <button onclick="toggleAnswer('a48')">答えを見る</button>
    <div class="answer" id="a48">
        <p><b>正解：SLCトランスポーター</b></p>
        <p>ポンプ、ABCトランスポーターの一次能動輸送。SLCトランスポーターの二次能動輸送。チャネルは構造変化を伴わず通路を開閉する。</p>
    </div>
</div>

<!-- Q49 -->
<div class="question">
    <p><b>49. 別の物質を反対方向に運ぶ輸送はどれか？</b></p>
    <button onclick="toggleAnswer('a49')">答えを見る</button>
    <div class="answer" id="a49">
        <p><b>正解：アンチポート</b></p>
        <p>アンチポートは互いに逆方向へ輸送する。シンポートは同方向。</p>
    </div>
</div>

<!-- Q50 -->
<div class="question">
    <p><b>50. 細胞からホウ素を排出するトランスポーターはどれか？</b></p>
    <button onclick="toggleAnswer('a50')">答えを見る</button>
    <div class="answer" id="a50">
        <p><b>正解：BOR1</b></p>
        <p>BOR1はホウ素排出トランスポーターで、ホウ素の長距離輸送に関わる。</p>
    </div>
</div>

<!-- Q51 -->
<div class="question">
    <p><b>51. 次の中で基本骨格にチッ素が必要なものはどれか？</b></p>
    <button onclick="toggleAnswer('a51')">答えを見る</button>
    <div class="answer" id="a51">
        <p><b>正解：タンパク質</b></p>
        <p>タンパク質はアミノ酸から構成され、アミノ基（–NH₂）を持つため窒素が必須。</p>
    </div>
</div>

<!-- Q52 -->
<div class="question">
    <p><b>52. 自然現象の中で土壌に大気中のチッ素を固定する役割を持つものはどれか？</b></p>
    <button onclick="toggleAnswer('a52')">答えを見る</button>
    <div class="answer" id="a52">
        <p><b>正解：雷</b></p>
        <p>雷の高温によりN₂が酸化され、硝酸イオンとして雨とともに土壌へ供給される。</p>
    </div>
</div>

<!-- Q53 -->
<div class="question">
    <p><b>53.（ア）とも呼ばれるアカウキクサは（イ）というラン藻類と共生することで窒素固定能力を持つ。このため，古来より水田の緑肥として利用されている。</b></p>
    <button onclick="toggleAnswer('a53')">答えを見る</button>
    <div class="answer" id="a53">
        <p><b>正解：ア：アゾラ　イ：アナベナ</b></p>
        <p>アカウキクサ（アゾラ）はアナベナと共生し窒素固定を行う。</p>
    </div>
</div>

<!-- Q54 -->
<div class="question">
    <p><b>54. マメ科植物と根粒菌の共生で正しい組み合わせはどれか？</b></p>
    <button onclick="toggleAnswer('a54')">答えを見る</button>
    <div class="answer" id="a54">
        <p><b>正解：ア：グルコース　イ：アンモニウムイオン</b></p>
        <p>植物は根粒菌に炭素源（グルコース）を与え、根粒菌は固定した窒素をアンモニウムとして提供する。</p>
    </div>
</div>

<!-- Q55 -->
<div class="question">
    <p><b>55. ニトロゲナーゼの説明で、一分子のチッ素を①して二分子のアンモニアを合成する。</b></p>
    <button onclick="toggleAnswer('a55')">答えを見る</button>
    <div class="answer" id="a55">
        <p><b>正解：①還元</b></p>
        <p>窒素固定は還元反応であり、N₂を還元してNH₃を生成する。酸化ではない。</p>
        <p>[1]反応に大量のエネルギー（ATP）を必要とする。[2]反応に必要な電子はフェレドキシンが供給する。[3]反応の進行にはモリブデンが必要である。
    </div>
</div>

<!-- Q56 -->
<div class="question">
    <p><b>56. マメ科植物と根粒菌の共生開始シグナルの正しい組み合わせはどれか？</b></p>
    <p><b>マメ科植物が根粒菌と共生するとき，マメ科植物側はダイゼインなどの（ア）を根より放出する。これを感知した根粒菌がNod因子と呼ばれる（イ）を合成，放出し，植物側に共生の準備を促す。</b></p>
    <button onclick="toggleAnswer('a56')">答えを見る</button>
    <div class="answer" id="a56">
        <p><b>正解：ア：フラボノイド化合物　イ：オリゴ糖類</b></p>
        <p>植物はフラボノイドを放出し、根粒菌はNod因子（オリゴ糖）を合成して共生を開始する。</p>
    </div>
</div>

<!-- Q57 -->
<div class="question">
    <p><b>57. 間違いはどれ？</b></p>
    <p><b>①根粒菌がエフェクターを用いて共生シグナルを直接活性化する経路をI型分泌系という。</b></p>
    <p><b>②根粒の中での根粒菌の存在形態をバクテロイドという</b></p>
    <p><b>③根粒菌が酸素を除去するために合成する物質の一つにヘモグロビンがある</b></p>
    <p><b>④植物根が根粒菌を巻き込む現象をカーリングという</b></p>
    <button onclick="toggleAnswer('a57')">答えを見る</button>
    <div class="answer" id="a57">
        <p><b>正解：①</b></p>
        <p>I型分泌系はタンパク質輸送の一般的分類であり、根粒菌の共生シグナル活性化とは異なる。</p>
    </div>
</div>

<!-- Q58 -->
<div class="question">
    <p><b>58. 窒素固定を行う微生物の正しい組み合わせはどれか？</b></p>
    <p><b>根粒菌以外で窒素固定を行う微生物には，ハンノキやヤマモモ属に共生する（ア）や，野生イネに共生する内生菌である（イ）などがある。</b></p>
    <button onclick="toggleAnswer('a58')">答えを見る</button>
    <div class="answer" id="a58">
        <p><b>正解：ア：フランキア　イ：Herbaspirillum</b></p>
        <p>フランキアはハンノキなどと共生し、Herbaspirillumは野生イネに共生する内生菌。</p>
    </div>
</div>

<!-- Q59 -->
<div class="question">
    <p><b>59. ハーバー・ボッシュ法は現在どこまで改善されたか？実験上①・②での反応が可能になった。</b></p>
    <button onclick="toggleAnswer('a59')">答えを見る</button>
    <div class="answer" id="a59">
        <p><b>正解：実験上①常温・②常圧での反応が可能になった</b></p>
        <p>触媒研究の進展により、実験レベルでは常温常圧でアンモニア合成が可能になっている。</p>
    </div>
</div>

<!-- Q60 -->
<div class="question">
    <p><b>60. 常温で液化可能で、水素燃料の代替として期待される化学物質はどれか？</b></p>
    <button onclick="toggleAnswer('a60')">答えを見る</button>
    <div class="answer" id="a60">
        <p><b>正解：アンモニア</b></p>
        <p>アンモニアは常温で容易に液化でき、エネルギーキャリアとして注目されている。</p>
    </div>
</div>

<!-- Q61 -->
<div class="question">
    <p><b>61. 同化作用に相当しないのは？</b></p>
    <p><b>吸収したイオウを使いシステインを合成する。</b></p>
    <p><b>硝酸イオンを吸収してアミノ酸を作る。</b></p>
    <p><b>デンプンを消費して発芽する。</b></p>
    <p><b>光合成で水と二酸化炭素からショ糖を作る。</b></p>
    <button onclick="toggleAnswer('a61')">答えを見る</button>
    <div class="answer" id="a61">
        <p><b>正解：デンプンを消費して発芽する</b></p>
        <p>同化作用は物質を合成する反応。発芽時のデンプン分解は異化作用である。</p>
    </div>
</div>

<!-- Q62 -->
<div class="question">
    <p><b>62. GS/GOGATサイクルではアンモニウムイオンはどの分子に付加され、何が合成されるか？</b></p>
    <button onclick="toggleAnswer('a62')">答えを見る</button>
    <div class="answer" id="a62">
        <p><b>正解：グルタミン酸に付加され、グルタミンが合成される</b></p>
        <p>GSはグルタミン酸にNH₄⁺を付加してグルタミンを作る。</p>
    </div>
</div>

<!-- Q63 -->
<div class="question">
    <p><b>63. 同じ炭素骨格（TCA回路・解糖系）を持つアミノ酸の組み合わせはどれか？</b></p>
    <p><b>    グルタミン・プロリン・アラニン</b></p>
    <p><b>　　トリプトファン・フェニルアラニン・メチオニン</b></p>
    <p><b>　　アスパラギン酸・トレオニン・リジン</b></p>
    <p><b>　　バリン・ロイシン・イソロイシン</b></p>
    <button onclick="toggleAnswer('a63')">答えを見る</button>
    <div class="answer" id="a63">
        <p><b>正解：アスパラギン酸・トレオニン・リジン</b></p>
        <p>いずれもピルビン酸を炭素骨格とする分岐鎖アミノ酸（BCAA）。</p>
    </div>
</div>

<!-- Q64 -->
<div class="question">
    <p><b>64. 芳香族アミノ酸の炭素骨格と、インドール系植物ホルモンの原料となるアミノ酸はどれか？</b></p>
    <button onclick="toggleAnswer('a64')">答えを見る</button>
    <div class="answer" id="a64">
        <p><b>正解：ホスホエノールピルビン酸（PEP）、トリプトファン</b></p>
        <p>芳香族アミノ酸はPEPとエリトロース4リン酸から合成される。</p>
    </div>
</div>

<!-- Q65 -->
<div class="question">
    <p><b>65. 一分子中の窒素原子数が最も多いものはどれか？</b></p>
    <button onclick="toggleAnswer('a65')">答えを見る</button>
    <div class="answer" id="a65">
        <p><b>正解：グアニン</b></p>
        <p>ポルフィリン環は4つのピロール環を持ち、窒素原子が多い。</p>
    </div>
</div>

<!-- Q66 -->
<div class="question">
    <p><b>66. イネの若い葉のタンパク質のうち、約75％がどこに分配され、そのうち約27％はどのタンパク質か？</b></p>
    <button onclick="toggleAnswer('a66')">答えを見る</button>
    <div class="answer" id="a66">
        <p><b>正解：葉緑体に分配され、そのうちRubiscoが大きな割合を占める</b></p>
        <p>Rubiscoは光合成に重要な酵素で、イネの若葉では特に多い。</p>
    </div>
</div>

<!-- Q67 -->
<div class="question">
    <p><b>67. 昔より窒素肥料は(ア)とよばれるが、これは窒素栄養が(イ)活性を介して植物の光合成量を左右することから、他の栄養素により成育に与える影響が大きいためである。</b></p>
    <button onclick="toggleAnswer('a67')">答えを見る</button>
    <div class="answer" id="a67">
        <p><b>正解：(ア)葉肥、(イ)Rubisco</b></p>
        <p>窒素は光合成酵素の合成に直結するため、葉の生育に大きく影響する。</p>
    </div>
</div>

<!-- Q68 -->
<div class="question">
    <p><b>68. 植物体内で機能を終えたタンパク質は(ア)酵素により修飾を受けた後、(イ)によりアミノ酸にまで分解され新しい組織で再利用される。</b></p>
    <button onclick="toggleAnswer('a68')">答えを見る</button>
    <div class="answer" id="a68">
        <p><b>正解：(ア)ユビキチン化、(イ)プロテアソーム</b></p>
        <p>ユビキチン化は分解対象のマーキングであり、プロテアソームが分解を行う。</p>
    </div>
</div>

<!-- Q69 -->
<div class="question">
    <p><b>69. 一般的な畑作物とは違い、イネや茶は(ア)態窒素を好む。(ア)のイオンは(イ)の電荷を持つことから土壌に保持されやすく、(ア)態窒素肥料は多雨の日本でよく利用される。</b></p>
    <button onclick="toggleAnswer('a69')">答えを見る</button>
    <div class="answer" id="a69">
        <p><b>正解：アンモニア態窒素（NH₄⁺）、正(プラス)電荷</b></p>
        <p>NH₄⁺は土壌に保持されやすく、日本の水田でよく利用される。</p>
    </div>
</div>

<!-- Q70 -->
<div class="question">
    <p><b>70. 窒素過剰施用で作物がどうなり、どのような葉の異常が起こるか？作物に窒素を過剰に施用するとセルロースなどの繊維質の割合が低下するための作物全体が(ア)する。またイチゴやきゅうりなどでは葉が成長しすぎ、果実などの収穫物の収量が低下する葉(イ)やつる(イ)が発生する。</b></p>
    <button onclick="toggleAnswer('a70')">答えを見る</button>
    <div class="answer" id="a70">
        <p><b>正解：軟化、ぼけ</b></p>
        <p>窒素過剰で細胞壁が薄くなり、葉が大きくなりすぎて果実の収量が低下する。</p>
    </div>
</div>

<!-- Q71 -->
<div class="question">
    <p><b>71. 肥料三要素の一つであるカリウムは何肥と呼ばれ、植物の乾燥重量あたり濃度は平均どれくらいか？</b></p>
    <button onclick="toggleAnswer('a71')">答えを見る</button>
    <div class="answer" id="a71">
        <p><b>正解：根肥・1.4%</b></p>
        <p>カリウムは根の生育や代謝調整に重要で「根肥」と呼ばれ、濃度は約1〜2%である。</p>
    </div>
</div>

<!-- Q72 -->
<div class="question">
    <p><b>72. 植物の葉において、カリウム濃度と高い相関を持つものは何か？</b></p>
    <button onclick="toggleAnswer('a72')">答えを見る</button>
    <div class="answer" id="a72">
        <p><b>正解：水分含量</b></p>
        <p>カリウムは浸透圧調節に関わるため、葉の水分量と強く相関する。</p>
    </div>
</div>

<!-- Q73 -->
<div class="question">
    <p><b>73. 葉緑体でATPが合成されるためには，チラコイド内腔側に対してストロマ側のpHを（ア）く維持する必要がある。デンプンの合成反応にはATPが必要なほか，デンプン合成酵素がカリウム施用によって活性化することから，カリウムは（イ）の時に施用効果が高いとされる。</b></p>
    <button onclick="toggleAnswer('a73')">答えを見る</button>
    <div class="answer" id="a73">
        <p><b>正解：ア高、イ日照不足</b></p>
        <p>ストロマ側がアルカリ性になることでATP合成が進み、高温時はデンプン合成酵素が活性化する。</p>
    </div>
</div>

<!-- Q74 -->
<div class="question">
    <p><b>74. カリウム輸送体によって吸収されてしまう有害物質は何か？</b></p>
    <button onclick="toggleAnswer('a74')">答えを見る</button>
    <div class="answer" id="a74">
        <p><b>正解：放射性セシウム</b></p>
        <p>セシウムはカリウムと化学的性質が似ており、同じ輸送体で吸収されてしまう。</p>
    </div>
</div>

<!-- Q75 -->
<div class="question">
    <p><b>75. 作物におけるカリウム欠乏の特徴として①が多い植物に発症しやすい？</b></p>
    <button onclick="toggleAnswer('a75')">答えを見る</button>
    <div class="answer" id="a75">
        <p><b>正解：炭水化物が多い植物に発症しやすい</b></p>
        <p>カリウムは糖の転流に関わるため、炭水化物を多く蓄積する作物で欠乏が顕著になる。</p>
    </div>
</div>

<!-- Q76 -->
<div class="question">
    <p><b>76. 植物細胞におけるカルシウム濃度は①どこに比べて②どこで低いか？</b></p>
    <button onclick="toggleAnswer('a76')">答えを見る</button>
    <div class="answer" id="a76">
        <p><b>正解：①細胞壁と液胞、②細胞質</b></p>
        <p>細胞質のCa²⁺濃度は極めて低く、シグナルとして利用される。</p>
        <p>細胞外と液胞は1~10mM,細胞質は0.1~1μM</p>
    </div>
</div>

<!-- Q77 -->
<div class="question">
    <p><b>77. カルシウムと共にペクチン鎖を架橋しゲル化する必須元素は何か？</b></p>
    <button onclick="toggleAnswer('a77')">答えを見る</button>
    <div class="answer" id="a77">
        <p><b>正解：ホウ素</b></p>
        <p>ホウ素は細胞壁のペクチン構造を安定化し、カルシウムと協調してゲル化を促す。</p>
    </div>
</div>

<!-- Q78 -->
<div class="question">
    <p><b>78. 植物のカルシウム吸収は土壌などの外界の濃度に依存する（ア）吸収である。その欠乏症は急速な細胞分裂を行う部位のほか，内葉など（イ）が起きにくい場所で発生しやすい</b></p>
    <button onclick="toggleAnswer('a78')">答えを見る</button>
    <div class="answer" id="a78">
        <p><b>正解：(ア)受動、(イ)蒸散</b></p>
        <p>Ca²⁺は蒸散流に依存して移動するため、内葉や果実など蒸散が少ない部位で欠乏しやすい。</p>
    </div>
</div>

<!-- Q79 -->
<div class="question">
    <p><b>79. カルシウム欠乏症の種類と発生作物の正しい組み合わせは何か？芯腐れ→①　チップバーン→②　尻腐れ→③</b></p>
    <button onclick="toggleAnswer('a79')">答えを見る</button>
    <div class="answer" id="a79">
        <p><b>正解：芯腐れ→白菜、チップバーン→イチゴ、尻腐れ→トマト</b></p>
        <p>Ca欠乏は蒸散の弱い部位で起こり、作物ごとに典型的な症状がある。</p>
    </div>
</div>

<!-- Q80 -->
<div class="question">
    <p><b>80. 全陸地のどれくらいが石灰質土壌であり、そのような土壌で溶解度が低下する微量元素は何か？</b></p>
    <button onclick="toggleAnswer('a80')">答えを見る</button>
    <div class="answer" id="a80">
        <p><b>正解：20%・鉄</b></p>
        <p>石灰質土壌はアルカリ性で、鉄などの微量要素が不溶化し欠乏を招く。</p>
    </div>
</div>

<!-- Q81 -->
<div class="question">
    <p><b>81. リンは昔より何肥と呼ばれていたか？</b></p>
    <button onclick="toggleAnswer('a81')">答えを見る</button>
    <div class="answer" id="a81">
        <p><b>正解：実肥・花肥</b></p>
        <p>リンは花や実の形成に強く関わるため、昔から「実肥・花肥」と呼ばれてきた。</p>
    </div>
</div>

<!-- Q82 -->
<div class="question">
    <p><b>82. 作物体内のリン濃度（乾燥重量あたり）はどれくらいか？</b></p>
    <button onclick="toggleAnswer('a82')">答えを見る</button>
    <div class="answer" id="a82">
        <p><b>正解：0.23%</b></p>
        <p>リンは必須栄養素だが、体内濃度は比較的低く、0.2〜0.3%程度である。</p>
    </div>
</div>

<!-- Q83（四択のまま） -->
<div class="question">
    <p><b>83. リン不足時の細胞内リン供給メカニズムについて、誤っているものはどれか？</b></p>
    <p>① 不足すると糖脂質をリン脂質に変換する<br>
       ② 過剰時は液胞に蓄積し、不足時は液胞から供給する<br>
       ③ グルクロノシルジアシルグリセロールを合成する植物がある<br>
       ④ MGDG や DGDG を合成して細胞膜機能を維持する</p>
    <button onclick="toggleAnswer('a83')">答えを見る</button>
    <div class="answer" id="a83">
        <p><b>正解：不足すると糖脂質をリン脂質に変換する</b></p>
        <p>リン不足時はリン脂質を糖脂質へ置き換える方向で調整する。</p>
    </div>
</div>

<!-- Q84 -->
<div class="question">
    <p><b>84. 黒ボク土において植物がリンを吸収しづらいのは，リンが黒ボク土の代表的な粘土鉱物である（ア）に含まれる（イ）と結合するためである</b></p>
    <button onclick="toggleAnswer('a84')">答えを見る</button>
    <div class="answer" id="a84">
        <p><b>正解：(ア)アロフェン、(イ)Al</b></p>
        <p>黒ボク土のアロフェンはAlを含み、リン酸と強く結合して固定化してしまう。</p>
    </div>
</div>

<!-- Q85（四択のまま） -->
<div class="question">
    <p><b>85. 植物のリン獲得機構として正しいものはどれか？</b></p>
    <p>① 根粒菌と共生してリンを獲得する<br>
       ② 有機リン化合物を分解するため有機酸を放出する<br>
       ③ 難溶性無機塩を可溶化するため酸性ホスファターゼを分泌する<br>
       ④ クラスター根を形成するなど根の形を変化させる</p>
    <button onclick="toggleAnswer('a85')">答えを見る</button>
    <div class="answer" id="a85">
        <p><b>正解：クラスター根の形成など根の形を変化する。</b></p>
        <p>①菌根菌と共生しリンを獲得する。②難溶性無機塩を可溶化するため有機酸の放出。③酸性ホスファターゼは有機態リンの分解。</p>
    </div>
</div>

<!-- Q86 -->
<div class="question">
    <p><b>86. </b>マメ科の植物である（ア）は根からの酸性ホスファターゼ分泌量が高く，リン不足の場合根から大量の（イ）を放出できることから，リンを施肥しなくても生育がほとんど落ちない。</p>
    <button onclick="toggleAnswer('a86')">答えを見る</button>
    <div class="answer" id="a86">
        <p><b>正解：(ア)ルーピンが大量の(イ)クエン酸を放出する</b></p>
        <p>ルーピンは酸性ホスファターゼ分泌量が高く、クエン酸でリンを可溶化する。</p>
    </div>
</div>

<!-- Q87 -->
<div class="question">
    <p><b>87. 次のうち、キノコになるものはどれか？</b></p>
    <button onclick="toggleAnswer('a87')">答えを見る</button>
    <div class="answer" id="a87">
        <p><b>正解：外生菌根菌</b></p>
        <p>外生菌根菌は子実体（キノコ）を形成する。アーバスキュラー菌根菌は形成しない。</p>
    </div>
</div>

<!-- Q88 -->
<div class="question">
    <p><b>88. アーバスキュラー菌根菌と共生しない植物はどれか？</b></p>
    <button onclick="toggleAnswer('a88')">答えを見る</button>
    <div class="answer" id="a88">
        <p><b>正解：キャベツ</b></p>
        <p>アブラナ科植物（キャベツなど）はアーバスキュラー菌根菌と共生しない。</p>
    </div>
</div>

<!-- Q89 -->
<div class="question">
    <p><b>89. 植物が菌根菌との共生を促すために放出するホルモンは何か？</b></p>
    <button onclick="toggleAnswer('a89')">答えを見る</button>
    <div class="answer" id="a89">
        <p><b>正解：ストリゴラクトン</b></p>
        <p>ストリゴラクトンは菌根菌を誘引し、共生を促進する重要なシグナル物質。</p>
    </div>
</div>

<!-- Q90 -->
<div class="question">
    <p><b>90. 土壌にリンが十分あるとき、植物が菌根菌の感染を抑制するために用いるホルモンは何か？</b></p>
    <button onclick="toggleAnswer('a90')">答えを見る</button>
    <div class="answer" id="a90">
        <p><b>ジベレリン</b></p>
    </div>
</div>

<!-- Q91 -->
<div class="question">
    <p><b>91. マグネシウムと共に葉緑体を構成する物質の組み合わせは何か？</b></p>
    <button onclick="toggleAnswer('a91')">答えを見る</button>
    <div class="answer" id="a91">
        <p><b>正解：クロリン環と長鎖アルコール</b></p>
        <p>クロロフィルはクロリン環とフィトール（長鎖アルコール）で構成される。</p>
    </div>
</div>

<!-- Q92（問題文そのまま） -->
<div class="question">
    <p><b>92. 次の（ア）と（イ）に入る言葉の組み合わせで正しいものを選択せよ</b></p>
    <p>Mgは植物のエネルギー代謝に重要な働きをもつ。これはMgが（ア）の酸素原子(O)と高い親和性があることから，（イ）と複合体を形成した上でエネルギー代謝に関わる主要な酵素の補因子として機能するためである。</p>
    <button onclick="toggleAnswer('a92')">答えを見る</button>
    <div class="answer" id="a92">
        <p><b>正解：(ア)リン酸イオン (イ)ATP</b></p>
        <p>Mg²⁺はリン酸基と結合し、ATP-Mg複合体として多くの酵素反応を助ける。</p>
    </div>
</div>

<!-- Q93 -->
<div class="question">
    <p><b>93. マグネシウムが関与しないものは？</b></p>
    <button onclick="toggleAnswer('a93')">答えを見る</button>
    <div class="answer" id="a93">
        <p><b>正解：細胞壁におけるペクチン鎖の架橋</b></p>
        <p>ペクチンの架橋は主にカルシウムとホウ素が関与し、Mgは関与しない。</p>
        <p>以下はマグネシウムが関与すること。</p>
        <p>生物時計の維持,リボソームの構造維持,ルビスコの触媒部位</p>
    </div>
</div>

<!-- Q94 -->
<div class="question">
    <p><b>94. イオウを含まない生体物質は？</b></p>
    <button onclick="toggleAnswer('a94')">答えを見る</button>
    <div class="answer" id="a94">
        <p><b>正解：グアニン</b></p>
        <p>グアニンは核酸塩基であり、硫黄を含まない。</p>
    </div>
</div>

<!-- Q95（四択のまま） -->
<div class="question">
    <p><b>95. 植物のイオウ欠乏に関する次の文章で、誤っているものはどれか？</b></p>
    <p>① 火山が多い日本ではあまりイオウ欠乏は発生しなかったが，現在は硫黄酸化物の規制強化による欠乏例が発生している<br>
       ② 含硫アミノ酸の不足によりタンパク質合成が低下するため，チッ素欠乏と似た症状が出る<br>
       ③ 下位葉（古葉）と共に生長点（上位葉）で黄化が顕著である<br>
       ④ タンパク質の少ないキュウリなどの栽培で欠乏が出ることが多い</p>
    <button onclick="toggleAnswer('a95')">答えを見る</button>
    <div class="answer" id="a95">
        <p><b>正解：タンパク質の少ないキュウリなどの栽培で欠乏が出ることが多い</b></p>
    </div>
</div>

<!-- Q96（問題文そのまま） -->
<div class="question">
    <p><b>96. 次の（ア）（イ）（ウ）の組み合わせで正しいものを選択せよ</b></p>
    <p>水田ではイオウ化合物の還元により有害な（ア）が発生するが，通常の水田土壌では（イ）と反応して（ウ）を形成するため，イネ根の害が発生しづらい。</p>
    <button onclick="toggleAnswer('a96')">答えを見る</button>
    <div class="answer" id="a96">
        <p><b>正解：硫化水素(H2S) × 鉄(Fe(Ⅱ)) × 硫化鉄(FeS)</b></p>
        <p>硫化水素（H₂S）は鉄と反応して硫化鉄となり、毒性が弱まる。</p>
    </div>
</div>

<!-- Q97 -->
<div class="question">
    <p><b>97. 日本の野生植物種のうち、最もイオウ含有量が高い科はどれか？</b></p>
    <button onclick="toggleAnswer('a97')">答えを見る</button>
    <div class="answer" id="a97">
        <p><b>正解：ユリ科</b></p>
        <p>ユリ科植物は硫黄含有量が高いことがXRF解析で示されている。</p>
    </div>
</div>

<!-- Q98 -->
<div class="question">
    <p><b>98. 植物の微量必須元素のうち、必須性が最も遅く認められたものは？</b></p>
    <button onclick="toggleAnswer('a98')">答えを見る</button>
    <div class="answer" id="a98">
        <p><b>正解：ニッケル（Ni）</b></p>
        <p>ニッケルはウレアーゼの構成元素として必須であることが比較的遅く判明した。</p>
    </div>
</div>

<!-- Q99 -->
<div class="question">
    <p><b>99. 植物細胞で最も鉄を含む器官は？</b></p>
    <button onclick="toggleAnswer('a99')">答えを見る</button>
    <div class="answer" id="a99">
        <p><b>正解：葉緑体</b></p>
        <p>葉緑体には鉄を含む電子伝達系タンパク質が多く存在する。</p>
    </div>
</div>

<!-- Q100 -->
<div class="question">
    <p><b>100. 次の中で鉄を含まないものは？</b></p>
    <button onclick="toggleAnswer('a100')">答えを見る</button>
    <div class="answer" id="a100">
        <p><b>正解：葉緑素</b></p>
        <p>葉緑素（クロロフィル）はMgを中心金属とし、鉄は含まない。</p>
    </div>
</div>

<!-- Q101 -->
<div class="question">
    <p><b>101. 土壌中よりも植物体内（被子植物）で濃度が高い元素は？</b></p>
    <button onclick="toggleAnswer('a101')">答えを見る</button>
    <div class="answer" id="a101">
        <p><b>正解：P（リン）</b></p>
        <p>リンは植物体内で濃縮されやすく、土壌より高濃度になる典型的な必須元素。</p>
    </div>
</div>

<!-- Q102（問題文そのまま） -->
<div class="question">
    <p><b>102. 次の（ア）（イ）に入る組みあわせで正しいものを選択せよ</b></p>
    <p>イネ科以外の植物のFe獲得機構Strategy-Iでは，植物は根からプロトンや（ア）を放出し，Fe(III)錯体を形成する。これをさらにFROと呼ばれる酵素で（イ）し，水に溶けやすいFe(II)の形で吸収する。</p>
    <button onclick="toggleAnswer('a102')">答えを見る</button>
    <div class="answer" id="a102">
        <p><b>正解：フェノール性キレート物質 × 還元</b></p>
        <p>Strategy-Iではフェノール性化合物でFe(III)をキレート化し、FROで還元してFe(II)として吸収する。</p>
    </div>
</div>

<!-- Q103（問題文そのまま） -->
<div class="question">
    <p><b>103. 次の（ア）（イ）に入る組みあわせで正しいものを選択せよ</b></p>
    <p>イネ科植物のFe獲得機構Strategy-IIでは，植物はキレート物質であるムギネ酸類を（ア）というトランスポーターを介して根の周りに放出し，土壌中の鉄を（イ）の状態でキレート化し，体内に取り込む。</p>
    <button onclick="toggleAnswer('a103')">答えを見る</button>
    <div class="answer" id="a103">
        <p><b>正解：TOM × Fe(III)</b></p>
        <p>Strategy-IIではムギネ酸類をTOMで放出し、Fe(III)-ムギネ酸錯体として吸収する。</p>
    </div>
</div>

<!-- Q104 -->
<div class="question">
    <p><b>104. ムギネ酸の前駆体でないものはどれか？</b></p>
    <button onclick="toggleAnswer('a104')">答えを見る</button>
    <div class="answer" id="a104">
        <p><b>正解：ニコチン</b></p>
        <p>ムギネ酸はメチオニン → ニコチアナミン → 2-デオキシムギネ酸などを経て合成される。</p>
    </div>
</div>

<!-- Q105 -->
<div class="question">
    <p><b>105. アメリカで鉄化合物の添加が認められている食品は？</b></p>
    <button onclick="toggleAnswer('a105')">答えを見る</button>
    <div class="answer" id="a105">
        <p><b>正解：小麦粉・トウモロコシ粉・米粉</b></p>
    </div>
</div>

<!-- Q106（問題文そのまま） -->
<div class="question">
    <p><b>106. 次の（ア）（イ）に入る組みあわせで正しいものを選択せよ</b></p>
    <p>銅はCu²⁺ ⇄ e⁻ + Cu⁺の酸化還元反応により電子の授受を担う。光化学系II→Iの電子伝達を担う（ア）や、ミトコンドリア電子伝達系で機能する（イ）などで必要とされる。</p>
    <button onclick="toggleAnswer('a106')">答えを見る</button>
    <div class="answer" id="a106">
        <p><b>正解：プラストシアニン × シトクロームCオキシダーゼ</b></p>
        <p>プラストシアニンは銅タンパク質で、ミトコンドリアのシトクロームCオキシダーゼも銅を含む。</p>
    </div>
</div>

<!-- Q107（問題文そのまま） -->
<div class="question">
    <p><b>107. 次の（ア）（イ）に入る組みあわせで正しいものを選択せよ</b></p>
    <p>北海道や東北などの（ア）の多い土壌では銅が吸着されやすく欠乏が起こる。ムギでは花粉母細胞の減数分裂異常により（イ）不稔が発生する。</p>
    <button onclick="toggleAnswer('a107')">答えを見る</button>
    <div class="answer" id="a107">
        <p><b>正解：腐植 × 雄性</b></p>
    </div>
</div>

<!-- Q108 -->
<div class="question">
    <p><b>108. SOD（スーパーオキシドジスムターゼ）の種類と機能する細胞内器官の正しい組み合わせはどれか？</b></p>
    <p><b>Fe-SOD:①，Cu/Zn-SOD：②,　Mn-SOD:③</b></p>
    <button onclick="toggleAnswer('a108')">答えを見る</button>
    <div class="answer" id="a108">
        <p><b>正解：Fe-SOD：①葉緑体、Cu/Zn-SOD：②細胞質、Mn-SOD：③ミトコンドリア</b></p>
        <p>各SODは異なる金属と局在を持ち、活性酸素除去に重要な役割を果たす。</p>
    </div>
</div>

<!-- Q109 -->
<div class="question">
    <p><b>109. OsNramp5遺伝子を壊すと吸収が抑制される有害金属はどれか？</b></p>
    <button onclick="toggleAnswer('a109')">答えを見る</button>
    <div class="answer" id="a109">
        <p><b>正解：カドミウム</b></p>
        <p>OsNramp5はMnとCdを輸送するため、遺伝子破壊によりCd吸収が大きく低下する。</p>
    </div>
</div>

<!-- Q110（四択のまま） -->
<div class="question">
    <p><b>110. 作物のマンガン欠乏について述べた文章の中で間違っているものはどれか？</b></p>
    <p>① 乾燥重量あたり20ppm以下で発症する<br>
       ② 光合成阻害によるクロロシスが野菜類では下位葉、ムギ類では上位葉で発生する<br>
       ③ ベニバナでは葉に斑点症状が発生することがある<br>
       ④ 水田からの転換畑などで発生しやすい</p>
    <button onclick="toggleAnswer('a110')">答えを見る</button>
    <div class="answer" id="a110">
        <p><b>正解：光合成阻害によるクロロシスが野菜類では下位葉、ムギ類では上位葉で発生する</b></p>
        <p>マンガンは移動性が低く、一般に新葉（上位葉）から症状が出るため、この記述は誤り。</p>
    </div>
</div>

<!-- Q111（文章そのまま） -->
<div class="question">
    <p><b>111. 次の（ア）と（イ）に入る言葉の組み合わせで正しいものを選択せよ</b></p>
    <p>亜鉛は細胞質における活性酸素除去酵素（Cu/Zn-SOD）に必要なほか，転写や翻訳に関わる（ア）などの酵素やリボソームの構造維持に必須である。そのためイネ種子では細胞分裂が盛んに行われる（イ）に亜鉛が蓄積される。</p>
    <button onclick="toggleAnswer('a111')">答えを見る</button>
    <div class="answer" id="a111">
        <p><b>正解：ポリメラーゼ × 胚芽</b></p>
        <p>亜鉛は核酸関連酵素に必須で、細胞分裂が盛んな胚芽に多く蓄積する。</p>
    </div>
</div>

<!-- Q112（文章そのまま） -->
<div class="question">
    <p><b>112. 次の（ア）と（イ）に入る言葉の組み合わせで正しいものを選択せよ</b></p>
    <p>水稲の節には（ア）細胞と呼ばれる，分裂組織に優先的に亜鉛を分配する役割を持つ細胞があることが知られていた。近年の遺伝子解析において，（イ）という金属輸送タンパク質がこの細胞に存在し，吸収した亜鉛を穂に分配することが明らかとなっている。</p>
    <button onclick="toggleAnswer('a112')">答えを見る</button>
    <div class="answer" id="a112">
        <p><b>正解：転移 × OsHMA2</b></p>
        <p>OsHMA2 は Zn の長距離転流に関わる主要トランスポーター。</p>
    </div>
</div>

<!-- Q113（四択のまま） -->
<div class="question">
    <p><b>113. 亜鉛欠乏症に関する次の文章で誤っているものを選択せよ</b></p>
    <p>① pHの低い土壌で発生しやすい<br>
       ② 小葉化など新葉、新芽の発育不良が発生する<br>
       ③ 乾燥重量あたり15mg/kg以下が欠乏症の目安である<br>
       ④ 下位葉クロロシスなどが発生する</p>
    <button onclick="toggleAnswer('a113')">答えを見る</button>
    <div class="answer" id="a113">
        <p><b>正解：① pHの低い土壌で発生しやすい</b></p>
        <p>亜鉛欠乏はアルカリ土壌（pHが高い）で発生しやすい。</p>
    </div>
</div>

<!-- Q114（文章そのまま） -->
<div class="question">
    <p><b>114. 次の（ア）（イ）（ウ）に入る言葉の組み合わせで正しいものを選択せよ</b></p>
    <p>植物にとってニッケルが必須元素である理由は，タンパク質の分解により体内で発生する（ア）を分解し，（イ）へと変換する（ウ）という酵素の活性中心として必要だからである。</p>
    <button onclick="toggleAnswer('a114')">答えを見る</button>
    <div class="answer" id="a114">
        <p><b>正解：アンモニア × 尿素 × ウレアーゼ</b></p>
        <p>ウレアーゼは Ni を含む酵素で、アンモニアを尿素へ変換する。</p>
    </div>
</div>

<!-- Q115 -->
<div class="question">
    <p><b>115. 蛇紋岩土壌で植物が不足を感知し、生育阻害を起こす元素はどれか？</b></p>
    <button onclick="toggleAnswer('a115')">答えを見る</button>
    <div class="answer" id="a115">
        <p><b>正解：鉄</b></p>
        <p>Ni 過剰により Fe の吸収が阻害され、鉄欠乏症状が出る。</p>
    </div>
</div>

<!-- Q116 -->
<div class="question">
    <p><b>116. 重度のニッケル過剰症で葉に褐色斑が現れる症状名はどれか？</b></p>
    <button onclick="toggleAnswer('a116')">答えを見る</button>
    <div class="answer" id="a116">
        <p><b>正解：ネクロシス</b></p>
        <p>細胞壊死により褐色斑が生じる典型的な過剰症状。</p>
    </div>
</div>

<!-- Q117 -->
<div class="question">
    <p><b>117. ホウ素と共に細胞壁のペクチンをゲル化する元素はどれか？</b></p>
    <button onclick="toggleAnswer('a117')">答えを見る</button>
    <div class="answer" id="a117">
        <p><b>正解：Ca</b></p>
        <p>カルシウムはホウ素と協調してペクチンを架橋し細胞壁を強化する。</p>
    </div>
</div>

<!-- Q118（文章そのまま） -->
<div class="question">
    <p><b>118. 次の（ア）（イ）に入る言葉の組み合わせで正しいものを選択せよ</b></p>
    <p>ホウ素は高濃度に存在すると細胞毒性を発揮するようになるため，土壌中にホウ素が過剰に存在する場合，植物は輸送体BOR1のタンパク質を（ア）し，エンドソームへ輸送したあと，最終的に（イ）に送って分解する。</p>
    <button onclick="toggleAnswer('a118')">答えを見る</button>
    <div class="answer" id="a118">
        <p><b>正解：ユビキチン化 × 液胞</b></p>
        <p>BOR1 はユビキチン化され、液胞で分解されることでホウ素過剰を防ぐ。</p>
    </div>
</div>

<!-- Q119（文章そのまま） -->
<div class="question">
    <p><b>119. 次の（ア）（イ）に入る言葉の組み合わせで正しいものを選択せよ</b></p>
    <p>モリブデンはプテリンと共にモリブデンコファクターを形成し，様々な酵素に利用される。例えば硝酸を亜硝酸に変換する（ア）や，根粒菌による窒素固定に利用される（イ）などである。</p>
    <button onclick="toggleAnswer('a119')">答えを見る</button>
    <div class="answer" id="a119">
        <p><b>正解：硝酸還元酵素 × ニトロゲナーゼ</b></p>
        <p>どちらもモリブデンを必要とする代表的酵素。</p>
    </div>
</div>

<!-- Q120 -->
<div class="question">
    <p><b>120. モリブデントランスポーターと同じグループの輸送体で吸収される必須元素はどれか？</b></p>
    <button onclick="toggleAnswer('a120')">答えを見る</button>
    <div class="answer" id="a120">
        <p><b>正解：ニッケル</b></p>
        <p>モリブデントランスポーター（MOT1/MOT2 系統）は、モリブデン（Mo）と同じくニッケル（Ni）を輸送できるグループに属している</p>
    </div>
</div>

<!-- Q121（問題文そのまま） -->
<div class="question">
    <p><b>121. 次の（ア）と（イ）に入る言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>ケイ素は地殻中において（ア）番目に多い元素であり，植物の中では（イ）において含有量が高い。</p>
    <button onclick="toggleAnswer('a121')">答えを見る</button>
    <div class="answer" id="a121">
        <p><b>正解：ア：2　イ：イネ科</b></p>
        <p>ケイ素は地殻中で2番目に多く、イネ科植物に多く蓄積される。</p>
    </div>
</div>

<!-- Q122（問題文そのまま） -->
<div class="question">
    <p><b>122. 次の（ア）と（イ）に入る言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>ケイ酸は水稲にさまざまな生物，化学，物理的な恩恵を与えるが，物理的な恩恵として台風などの強風による（ア）の抑制や，病原菌感染の抑制，イネの代表的な害虫である（イ）の害を軽減するなどの機能を持つ。</p>
    <button onclick="toggleAnswer('a122')">答えを見る</button>
    <div class="answer" id="a122">
        <p><b>正解：ア：倒伏　イ：ウンカ</b></p>
        <p>ケイ酸は稈を強化し倒伏を防ぎ、ウンカ被害も軽減する。</p>
    </div>
</div>

<!-- Q123（特別形式：3つの解答欄） -->
<div class="question">
    <p><b>123. Lsi1, Lsi2, Lsi6 のケイ酸輸送について、それぞれどこからどこに分配されるか答えよ</b></p>

    <button onclick="toggleAnswer('a123')">答えを見る</button>
    <div class="answer" id="a123">
        <p><b>Lsi1：</b>細胞の外 → 中（取り込み）</p>
        <p><b>Lsi2：</b>細胞の中 → 外（排出）</p>
        <p><b>Lsi6：</b>導管 → 葉・茎（地上部への分配）</p>
        <p>※ケイ酸は根で Lsi1 により取り込まれ、Lsi2 により外側へ排出され、Lsi6 により地上部へ運ばれる。</p>
    </div>
</div>

<!-- Q124（問題文そのまま） -->
<div class="question">
    <p><b>124. 次の（ア）（イ）に入る言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>アルミニウムはリン酸過剰の影響を緩和するため，（ア）にとっては有用元素として働く。一方，酸性土壌で溶解したアルミニウムは細胞壁などに結合し，（イ）の伸長を阻害する有害作用を持つ。</p>
    <button onclick="toggleAnswer('a124')">答えを見る</button>
    <div class="answer" id="a124">
        <p><b>正解：ア：チャ　イ：根</b></p>
        <p>チャはリン酸過剰を Al が緩和するが、酸性土壌では根の伸長阻害が起こる。</p>
    </div>
</div>

<!-- Q125 -->
<div class="question">
    <p><b>125. イネやキャベツなどでナトリウムが代替できる元素はどれか？</b></p>
    <button onclick="toggleAnswer('a125')">答えを見る</button>
    <div class="answer" id="a125">
        <p><b>正解：カリウム</b></p>
        <p>Na は K の代替として浸透圧形成に寄与することがある。</p>
    </div>
</div>

<!-- Q126（問題文そのまま） -->
<div class="question">
    <p><b>126. 次の（ア）（イ）に入る言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>コバルトを含むビタミンである（ア）は，（イ）による窒素固定に必要であることから，マメ科植物にとって有用である。</p>
    <button onclick="toggleAnswer('a126')">答えを見る</button>
    <div class="answer" id="a126">
        <p><b>正解：ア：ビタミンB12　イ：根粒菌</b></p>
        <p>ビタミンB12 は根粒菌の窒素固定に必須である。</p>
    </div>
</div>

<!-- Q127（問題文そのまま） -->
<div class="question">
    <p><b>127. 次の（ア）（イ）に入る言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>カドミウムは（ア）の原因として知られる有害元素であるが，イネは（イ）という遺伝子の機能を破壊することでカドミウムの吸収を抑えることができる。</p>
    <button onclick="toggleAnswer('a127')">答えを見る</button>
    <div class="answer" id="a127">
        <p><b>正解：ア：イタイイタイ病　イ：OsNRAMP5</b></p>
        <p>OsNRAMP5 は Cd の主要吸収経路であり、破壊により低Cd化が可能。</p>
    </div>
</div>

<!-- Q128（問題文そのまま） -->
<div class="question">
    <p><b>128. 次の（ア）（イ）に入る言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>ヒ素は（ア）地帯の土壌に比較的多く存在する。イネ体内でヒ素は（イ）というキレート能を持つペプチドと結合しやすい。</p>
    <button onclick="toggleAnswer('a128')">答えを見る</button>
    <div class="answer" id="a128">
        <p><b>正解：ア：火山　イ：ファイトケラチン</b></p>
        <p>ヒ素（As）は植物体内で ファイトケラチン（phytochelatin） と強く結合して解毒されることが知られている。</p>
    </div>
</div>

<!-- Q129（問題文を指定内容に変更済み） -->
<div class="question">
    <p><b>129. イネ中のカドミウムは(ア)水田で，ヒ素は(イ)水田で多くなる。ヒ素抑制には(ウ)の利用が有効。</b></p>
    <button onclick="toggleAnswer('a129')">答えを見る</button>
    <div class="answer" id="a129">
        <p><b>正解：ア：落水　イ：湛水　ウ：鉄資材</b></p>
        <p>Cd は落水で増え、As は湛水で増える。鉄資材はヒ素固定に有効。</p>
    </div>
</div>

<!-- Q130（問題文そのまま） -->
<div class="question">
    <p><b>130. 次の（ア）（イ）に入る言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>イネ体内に放射性セシウムは主に必須元素の（ア）の吸収経路を介して吸収される。ゆえに，イネへの放射性セシウムの蓄積は（ア）の高親和性トランスポーターである（イ）の変異によって抑制できる。</p>
    <button onclick="toggleAnswer('a130')">答えを見る</button>
    <div class="answer" id="a130">
        <p><b>正解：ア：カリウム　イ：OsHAK1</b></p>
        <p>Cs は K と同じ経路で吸収されるため、OsHAK1 の変異で抑制可能。</p>
    </div>
</div>

<!-- Q131（問題文そのまま） -->
<div class="question">
    <p><b>131. 「植物は有機物に依存しないで無機栄養を営む」という考えを提唱し，窒素・リン酸・カリウムの三要素説や最小養分律などを提唱した人物はだれか？</b></p>
    <button onclick="toggleAnswer('a131')">答えを見る</button>
    <div class="answer" id="a131">
        <p><b>正解：ユストゥス・フォン・リービッヒ</b></p>
    </div>
</div>

<!-- Q132（問題文そのまま） -->
<div class="question">
    <p><b>132. 全人類が消費しているエネルギーのなかで，チッ素肥料の合成に利用されている割合はどのくらいか？</b></p>
    <button onclick="toggleAnswer('a132')">答えを見る</button>
    <div class="answer" id="a132">
        <p><b>正解：約1%</b></p>
    </div>
</div>

<!-- Q133（4択のまま） -->
<div class="question">
    <p><b>133. 兵庫県加西市の長期イネ栽培試験で、肥料無施用時に最も生育に影響した成分はどれか？</b></p>
    <p>① チッ素<br>
       ② リン<br>
       ③ カリウム<br>
       ④ マグネシウム</p>
    <button onclick="toggleAnswer('a133')">答えを見る</button>
    <div class="answer" id="a133">
        <p><b>正解：チッ素</b></p>
        <p>長期試験では窒素欠乏が最も顕著に生育を阻害した。</p>
    </div>
</div>

<!-- Q134（問題文と解答をそのままHTML化） -->
<div class="question">
    <p><b>134. 次のうち，化学肥料の特性について述べたものを選択せよ</b></p>

    <p>動植物原料が主体で、肥効が現れるためには土壌中で分解される必要がある</p>
    <p>工業的に大量に作られるため安定供給ができ、品質も一定である。</p>
    <p>有効成分含量が低い</p>
    <p>微量要素などの副成分を含み、土壌の物理性や生物性を改善する効果が期待できる。</p>

    <button onclick="toggleAnswer('a134')">答えを見る</button>
    <div class="answer" id="a134">
        <p><b>正解：工業的に大量に作られるため安定供給ができ、品質も一定である。</b></p>
    </div>
</div>

<!-- Q135 -->
<div class="question">
    <p><b>135. 硝安（硝酸アンモニウム）の化学式は何か？</b></p>
    <button onclick="toggleAnswer('a135')">答えを見る</button>
    <div class="answer" id="a135">
        <p><b>正解：NH₄NO₃</b></p>
        <p>硝酸アンモニウムは窒素肥料として広く利用される。</p>
    </div>
</div>

<!-- Q136（問題文そのまま） -->
<div class="question">
    <p><b>136. 次のなかで，イオウの供給も見込まれる肥料はどれか？</b></p>
    <button onclick="toggleAnswer('a136')">答えを見る</button>
    <div class="answer" id="a136">
        <p><b>正解：硫酸カリウム</b></p>
        <p>硫酸カリウムはKと同時にSも供給できる。</p>
    </div>
</div>

<!-- Q137（問題文そのまま） -->
<div class="question">
    <p><b>137. 次の（ア）（イ）に入る言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>アンモニウム塩、硝酸塩、尿素などの肥料は水溶性で吸収されやすく、（ア）的であることから，樹脂などで肥料粒子を覆った被服肥料が開発されている。この肥料は作物への（イ）障害を軽減し，かつ土壌への固定も抑制するメリットを持つ。</p>
    <button onclick="toggleAnswer('a137')">答えを見る</button>
    <div class="answer" id="a137">
        <p><b>正解：ア：速効　イ：濃度</b></p>
        <p>被覆肥料は肥料濃度障害を防ぎ、肥効を調整できる。</p>
    </div>
</div>

<!-- Q138（写真は後で貼る） -->
<div class="question">
    <p><b>138. 写真のように、イネ苗の根に一作分の被覆肥料を絡めて育苗し、そのまま田植機で移植する方法をなんと呼ぶか？</b></p>
    <p><i><img src="C:\Users\kaho owner\OneDrive - 三重大学\3年\html作り\植物栄養学14.1.png"  width="300" height="200"></i></p>
    <button onclick="toggleAnswer('a138')">答えを見る</button>
    <div class="answer" id="a138">
        <p><b>正解：弁当肥</b></p>
        <p>苗に肥料を「持たせて」移植するため弁当肥と呼ばれる。</p>
    </div>
</div>

<!-- Q139（指定内容に変更済み） -->
<div class="question">
    <p><b>139. 過リン酸石や重過リン酸石灰の主要成分であるリン酸第一カルシウム(リン酸二水素カルシウム)の化学式を選択せよ</b></p>
    <button onclick="toggleAnswer('a139')">答えを見る</button>
    <div class="answer" id="a139">
        <p><b>正解：Ca(H2PO4)2・H2O</b></p>
    </div>
</div>

<!-- Q140（問題文そのまま） -->
<div class="question">
    <p><b>140. カリウム資源量および生産量が世界で最も大きな国はどれか？</b></p>
    <button onclick="toggleAnswer('a140')">答えを見る</button>
    <div class="answer" id="a140">
        <p><b>正解：カナダ</b></p>
        <p>カナダは世界最大のカリウム資源国であり、生産量も最大。</p>
    </div>
</div>

<!-- Q141（問題文そのまま） -->
<div class="question">
    <p><b>141. 次の（ア）（イ）に入る言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>土壌のpHを上げるために菜園などで使われる苦土石灰は（ア）という鉱物を加熱し、砕いて粉状もしくは粒状にした肥料であり，含まれるカルシウムとマグネシウムの比が約（イ）となっている。</p>
    <button onclick="toggleAnswer('a141')">答えを見る</button>
    <div class="answer" id="a141">
        <p><b>正解：ア：ドロマイト　イ：2：1</b></p>
        <p>苦土石灰はドロマイト（CaMg(CO₃)₂）を原料とし、Ca:Mg ≈ 2:1 の比率になる。</p>
    </div>
</div>

<!-- Q142 -->
<div class="question">
    <p><b>142. 消石灰を次から選択せよ（数字は下付き）</b></p>
    <button onclick="toggleAnswer('a142')">答えを見る</button>
    <div class="answer" id="a142">
        <p><b>正解：Ca(OH)₂</b></p>
        <p>消石灰は水酸化カルシウムであり、強いアルカリ性を示す。</p>
    </div>
</div>

<!-- Q143 -->
<div class="question">
    <p><b>143. 次の説明に相当する元素を選択せよ。</b></p>
    <p>菜種やテンサイで必要量が多く、欠乏しやすいことから微量要素肥料として認められている。</p>
    <button onclick="toggleAnswer('a143')">答えを見る</button>
    <div class="answer" id="a143">
        <p><b>正解：B（ホウ素）</b></p>
        <p>ホウ素はアブラナ科やテンサイで要求量が高く、欠乏しやすい典型元素。</p>
    </div>
</div>

<!-- Q144（4択のまま） -->
<div class="question">
    <p><b>144. 肥料取締法による普通肥料に分類されるものは？</b></p>
    <button onclick="toggleAnswer('a144')">答えを見る</button>
    <div class="answer" id="a144">
        <p><b>正解：汚泥</b></p>
        <p>これは普通肥料として登録されている代表例。</p>
    </div>
</div>

<!-- Q145 -->
<div class="question">
    <p><b>145. 肥料取締法による特殊肥料に分類されるものを挙げよ。</b></p>
    <button onclick="toggleAnswer('a145')">答えを見る</button>
    <div class="answer" id="a145">
        <p><b>正解：魚かす、米ぬか、コーヒーかす、干蚕蛹、骨灰</b></p>
        <p>これらは特殊肥料として登録されている代表例。</p>
    </div>
</div>

<!-- Q146（問題文そのまま） -->
<div class="question">
    <p><b>146. 堆肥製造の注意について述べた次の文章において，（ア）と（イ）に相当する言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>未熟な堆肥は（ア）分解性の有機物を多量に含んでおり，土壌に投入すると微生物により急激に分解される。その際（イ）が大量に消費されるため，植物根が酸欠となる場合がある。</p>
    <button onclick="toggleAnswer('a146')">答えを見る</button>
    <div class="answer" id="a146">
        <p><b>正解：ア：易　イ：O₂</b></p>
        <p>未熟堆肥は易分解性物質が多く、分解時に酸素が大量消費される。</p>
    </div>
</div>

<!-- Q147 -->
<div class="question">
    <p><b>147. 家畜ふん堆肥の腐熟が進行する際、微生物により最後に分解される成分はどれか？</b></p>
    <button onclick="toggleAnswer('a147')">答えを見る</button>
    <div class="answer" id="a147">
        <p><b>正解：リグニン</b></p>
        <p>リグニンは難分解性であり、腐熟の最終段階で分解される。</p>
    </div>
</div>

<!-- Q148（問題文そのまま、写真は後で貼る） -->
<div class="question">
    <p><b>148. 次の説明に相当する土壌の種類を選択せよ。</b></p>
    <p>牛糞堆肥は鶏糞堆肥よりN, P, Kの各種成分量が（ア）が，ワラやおがくず、籾殻などが混入し，腐植質が比較的豊富に含まれるため，高い（イ）が見込まれる。</p>
    <p><i>（写真は後で貼付）</i></p>
    <button onclick="toggleAnswer('a148')">答えを見る</button>
    <div class="answer" id="a148">
        <p><b>正解：ア：少ない　イ：土壌改良効果</b></p>
        <p>牛糞堆肥は肥効よりも土壌改良効果が高い。</p>
    </div>
</div>

<!-- Q149（問題文そのまま） -->
<div class="question">
    <p><b>149. 次の（ア）（イ）に入る言葉の組みあわせで正しいものを選択せよ</b></p>
    <p>（ア）とは作物の植え付け前や播種前に土壌に与える肥料のことであり，（イ）とは栽培期間が長い作物に適切な時期に肥料を追加することである。</p>
    <button onclick="toggleAnswer('a149')">答えを見る</button>
    <div class="answer" id="a149">
        <p><b>正解：ア：基肥　イ：追肥</b></p>
        <p>基肥は最初に施す肥料、追肥は生育途中で追加する肥料。</p>
    </div>
</div>

<!-- Q150 -->
<div class="question">
    <p><b>150. 「肥料の施用効果は，土壌中の養分が少ないほど大きく，施用量が増えると増収効果は次第に低減する」この原理をなんと呼ぶか？</b></p>
    <button onclick="toggleAnswer('a150')">答えを見る</button>
    <div class="answer" id="a150">
        <p><b>正解：収量漸減の法則</b></p>
        <p>肥料効果は初期ほど大きく、量を増やすほど限界効用が低下する。</p>
    </div>
</div>

