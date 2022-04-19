
////////////////okooob/////////////////////
$date = $_GET['date'];
$url = "http://a.okooo.com/I/?method=mc.data.schedule.getOkoooSchedule&LotteryType=SportteryHWL&LotteryNo=";
$game_url = $url . $date;
$data = file_get_contents($game_url);
echo $data;
exit;

////////////////okooob/////////////////////
////////////////okooo/////////////////////

$date = $_GET['date'];
$url = "http://a.okooo.com/I/?method=mc.data.schedule.getOkoooSchedule&LotteryType=SportterySoccerMix&LotteryNo=";
$game_url = $url . $date;
$data = file_get_contents($game_url);
echo $data;
exit
////////////////okooo/////////////////////
