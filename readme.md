JBoss AS 7 için Postgresql JDBC modülü
=================================

JBoss AS 7 için Postgresql sürücü bağlantısını bir JBoss Module olarak oluturur ve istenirse yüklemesini yapar.

Kullanımı
---------------------------------

1. Öncelikle JBoss AS 7'nin çalıştığından emin olun
2. `mvn assembly:assembly` komutu ile target altında gerekli dosyaları olşturun
3. target/as7-module-pgsql-version-module klasöründe `./install.sh [JBOSS_HOME]` komutunu çalıştırın

Not: [JBOSS_HOME] JBoss AS 7 Klasörünün rootunu göstermeli, Örnek : **/home/haky/Apps/jboss-as-7.1.1** şeklinde
