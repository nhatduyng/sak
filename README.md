<?php
@system("clear")
if ($function=1){
  @system("clear");
  echo "Sử Dụng 1 TAB\n\rTài khoản:";
  $username=trim(fgets(STDIN));
  echo "Mật khẩu:";
  $password=trim(fgets(STDIN));
  if (!username || !password){
    @system("clear");
    echo "Nhập Thông Tin\r\n";
    sleep(2);
    exit("Đăng Xuất\r\n");
    
  }
}
function login($url, $data){
  $ch=curl_init();
  curl_setopt_array($ch ,array(
    ))
}
