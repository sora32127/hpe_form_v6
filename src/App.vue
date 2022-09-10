<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <title>健常者エミュレータ事例集Wiki投稿フォーム v2.1</title>
    <meta name="description" content="Created by contradiction29" />

    <h1>健エミュWiki投稿補助ツール</h1>
    <br>

    <h2>禁止事項</h2>
        <li>経験談ではない記事を投稿してはいけない</li>
        <li>基本的人権を否定する投稿をしてはいけない</li>
        <li>誹謗中傷や個人攻撃、暴言、プライバシー違反を含む投稿をしてはいけない</li>      
        <li>幼児的かつ性的な表現を含めてはいけない</li>
    <br>

    <h2>使い方</h2>
      <ol>
        <li>下の「分類」から、投稿したいエピソードに合わせて「やってはいけないこと」と「やってよかったこと」のどちらかを選択します。</li>
        <li>空欄を埋めます。適時右上のボタンを押して確認することができます。</li>
        <li>「クリップボードに貼り付けてSeesaa Wiki投稿ページに移動」ボタンを押します。</li>
        <li>Seesaa Wikiの投稿画面に遷移します。投稿用テキストボックスにペーストします。</li>
        <li>タイトルを入力します。</li>
        <li>画像認証を入力し、「保存」を押すことで投稿できます。</li>
      </ol>
    <br>

    <h2>分類</h2>
    <input type = "radio" name = "type" checked/>やってはいけないこと<br>
    <input type = "radio" name = "type">やってよかったこと

    <h2>5W1H+Then状況説明</h2>
      <p>状況を思い出してください。</p>
      <h3 class="h3">その状況の「主役」は誰ですか？(Who)</h3>
      <h3>いつ起こったことですか？(When)</h3>
      <h3>どこで起こったことですか？(Where)</h3>
      <h3>なぜそのような行動をしたのですか？(Why)</h3>  
      <h3>その主役は、何に対してはたらきかけましたか？(What)</h3>
      <h3>その主役は、対象をどうしましたか？(How)</h3>     
      <h3>行動の結果としてどうなりましたか？(Then)</h3>
    <br>

    <h2>健常行動ブレイクポイント</h2>
    <p>上で記述した状況がどのような点でアウトだったのかの説明です。
      できる範囲で構わないので、なるべく理由は深堀りしてください。
      「マナーだから」は理由としては認められません。
      健常者エミュレータはマナー講師ではありません。</p>
    <p>一つずつ追加してください。3つ記入する必要はありません。</p>
    <br>

    <h2>どうすればよかったか</h2>
    <p>5W1H状況説明、健常行動ブレイクポイントを踏まえ、どのようにするべきだったかを提示します。</p>
    <br>

    <h2>備考</h2>
    <p>書ききれなかったことを書きます</p>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
