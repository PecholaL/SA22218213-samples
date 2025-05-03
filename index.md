# 基于语音表征学习的零样本语音转换及说话人匿名研究

## 说明
<p align="justify">
本页面提供2025年中国科学技术大学工程硕士学位论文《基于语音表征学习的零样本语音转换及说话人匿名研究》的音频样本，以展示文中“互信息和孪生结构增强的语音转换模型”及“生成匿名表征的说话人匿名模型”的效果。前者与本学位论文作者发表于IJCNN 2025的文章MAIN-VC: Lightweight Speech Representation Learning for One-Shot Voice Conversion一致，故本页中语音转换的音频样本来自MAIN-VC的demo page。
</p>

## 语音转换任务音频样本
表中“M2F”为“男性说话人到女性说话人的语音转换”的简称，M2M、F2M、F2F等简称同理。

<script>
function pauseOthers(ele) {
    $("audio").not(ele).each(function (index, audio) {audio.pause();});
}
</script>

<style>
.main-content table {
    display: inline-table;
}
table {
    table-layout:fixed;
    width: 100%;
    overflow: hidden;
}
#player{
    width: 100%;
}
</style>

<table>
	<CAPTION>表1 任意说话人到任意说话人语音转换（零样本语音转换）任务中的语音音频样本</CAPTION>
    <tr>
        <th>  </th>
	<th> 源语音 </th>
        <th> 目标语音 </th>
	<th> 转换语音 </th>
    </tr>
<tr>
        <th> F2F </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vcraw/p225_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vcraw/p268_004.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vc/F2Fp225_001_p268_004.mp3" type="audio/mpeg"></audio> </th>
</tr>
	
<tr>
        <th> M2M </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vcraw/p345_112.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vcraw/p360_012.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vc/M2Mp345_112_p360_012.mp3" type="audio/mpeg"></audio> </th>
</tr>

<tr>
        <th> F2M </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vcraw/p225_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vcaw/p360_010.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vc/F2Mp225_001_p360_010.mp3" type="audio/mpeg"></audio> </th>
</tr>
    
<tr>
        <th> M2F </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vcraw/p345_058.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vcraw/p268_062.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vc/M2Fp345_058_p268_062.mp3" type="audio/mpeg"></audio> </th>
</tr>
</table>

<p>&nbsp;</p> 


## 说话人匿名任务音频样本

<script>
function pauseOthers(ele) {
    $("audio").not(ele).each(function (index, audio) {audio.pause();});
}
</script>

<table>
	<CAPTION>表2 说话人匿名任务中的语音音频样本</CAPTION>
    <tr>
	<th> 原始语音 </th>
        <th> 匿名语音 </th>
    </tr>
<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/spkAno/p229_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/spkAno/p229_001_ano.mp3" type="audio/mpeg"></audio> </th>
</tr>
	
<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/spkAno/p251_010.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/spkAno/p251_010_ano.mp3" type="audio/mpeg"></audio> </th>
</tr>

<tr>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/spkAno/p280_182.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/spkAno/p280_182_ano.mp3" type="audio/mpeg"></audio> </th>
</tr>
</table>

