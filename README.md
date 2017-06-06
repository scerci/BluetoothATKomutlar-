# BluetoothATKomutlar-
Bluetooth modülünün AT komutları

AT komutu doğrulamak için kullanılır. Eğer bağlantı doğru kurulmuşsa OK cevabını alırsınız.

AT+PSWD? komutu bluetoothun eşleşme şifresini öğrenmek için kullanılır.

AT+PSWD=xxxx komutu eşleşme şifresini değiştirmek için kullanılır. (xxxx sisin belirlediğiniz bir şifredir)

AT+NAME? komutu bluetooth’un görünen adınının ne olduğunu öğrenmek için kullanılır.

AT+NAME=xxxx komutu bluetooth’un görünen adını değiştirmek için kullanılır. (xxxx burada sizin belirlediğiniz bir isimdir)

AT+ROLE? komutu modülün slave/master yada loopback modunda olup olmadığını sorgular

AT+ROLE=0 komutu modülün slave, AT+ROLE=1 komutu modülün master, AT+ROLE=2 ise slaveloop moduna girmesini sağlar.
