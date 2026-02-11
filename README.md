# PostgreSQL Veteriner Kliniği Sistemi

Bu proje, bir veteriner kliniği için geliştirilmiş veri tabanı sistemidir.  
PostgreSQL kullanılarak **hayvan, sahip, hasta hayvan, aşı ve randevu** kayıtları yönetilmektedir.  
Projede ayrıca **views** ve **triggers** ile veri yönetimi otomatikleştirilmiştir.

## Veri Yapısı ve Kurallar
- Her hayvanın **tek bir sahibi** vardır.  
- Bir sahibi **birden fazla hayvana** sahip olabilir.  
- Hasta hayvanların aşı ve randevu bilgileri tutulur.

## Özellikler
- Hayvan ve sahip kayıtlarını ekleme, güncelleme ve silme  
- Hasta hayvanların aşı ve randevu takibi  
- **Views** ile sık kullanılan sorgular kolay erişilebilir  
- **Triggers** ile veri bütünlüğü ve otomatik işlemler sağlanır  
- `backup.sql` dosyası ile veri tabanı yedeği

## Kullanım
1. PostgreSQL kurulumu yapılmalı  
2. `backup.sql` dosyası import edilerek veri tabanı oluşturulabilir  
3. SQL sorguları ile kayıtlar yönetilebilir

## Teknolojiler
- PostgreSQL
- SQL
