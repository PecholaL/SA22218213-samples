# 基于语音表征学习的零样本语音转换及说话人匿名研究

## 说明
<p align="justify">
本页面提供2025年中国科学技术大学工程硕士学位论文《基于语音表征学习的零样本语音转换及说话人匿名研究》的音频样本，以展示文中“互信息和孪生结构增强的语音转换模型”及“生成匿名表征的说话人匿名模型”的效果。前者与本学位论文作者发表于IJCNN 2025的文章*MAIN-VC: Lightweight Speech Representation Learning for One-Shot Voice Conversion*一致，故音频样本沿用了MAIN-VC的demo page。
</p>

## Audio Samples in VC Tasks
Audio samples are taken from the VCTK dataset and AISHELL dataset.

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
	<CAPTION>表1 多说话人对多说话人语音转换任务中的语音音频样本</CAPTION>
    <tr>
        <th>  </th>
	<th> Source </th>
        <th> Target </th>
	<th> MAIN-VC </th>
    </tr>
<tr>
        <th> F2F </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/s2s_raw/p228_154.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/s2s_raw/p233_025.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vc/s2s/F2Fp228_154_p233_025.mp3" type="audio/mpeg"></audio> </th>
</tr>
	
<tr>
        <th> M2M </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/s2s_raw/p374_070.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/s2s_raw/p286_028.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vc/s2s/M2Mp374_070_p286_028.mp3" type="audio/mpeg"></audio> </th>
</tr>

<tr>
        <th> F2M </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/s2s_raw/p313_300.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/s2s_raw/p363_041.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vc/s2s/F2Mp313_300_p363_041.mp3" type="audio/mpeg"></audio> </th>
</tr>
    
<tr>
        <th> M2F </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/s2s_raw/p270_234.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/s2s_raw/p265_148.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/vc/s2s/M2Fp270_234_p265_148.mp3" type="audio/mpeg"></audio> </th>
</tr>	
</table>

<p>&nbsp;</p> 

<table>
	<CAPTION>表2 任意说话人到任意说话人语音转换（零样本语音转换）任务中的语音音频样本</CAPTION>
    <tr>
        <th>  </th>
	<th> Source </th>
        <th> Target </th>
        <th> Baseline </th>
	<th> MAIN-VC </th>
    </tr>
<tr>
        <th> F2F </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/u2u_raw/p225_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/u2u_raw/p268_004.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/ADAINVC/u2u/p225_001_p268_004.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/MAINVC/u2u/F2Fp225_001_p268_004.mp3" type="audio/mpeg"></audio> </th>
</tr>
	
<tr>
        <th> M2M </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/u2u_raw/p345_112.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/u2u_raw/p360_012.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/ADAINVC/u2u/p345_112_p360_012.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/MAINVC/u2u/M2Mp345_112_p360_012.mp3" type="audio/mpeg"></audio> </th>
</tr>

<tr>
        <th> F2M </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/u2u_raw/p225_001.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/u2u_raw/p360_010.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/ADAINVC/u2u/p225_001_p360_010.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/MAINVC/u2u/F2Mp225_001_p360_010.mp3" type="audio/mpeg"></audio> </th>
</tr>
    
<tr>
        <th> M2F </th>
	<th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/u2u_raw/p345_058.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/u2u_raw/p268_062.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/ADAINVC/u2u/p345_058_p268_062.mp3" type="audio/mpeg"></audio> </th>
        <th> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/MAINVC/u2u/M2Fp345_058_p268_062.mp3" type="audio/mpeg"></audio> </th>
</tr>
</table>

<p>&nbsp;</p> 



