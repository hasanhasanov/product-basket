# .NET 7 Product&Basket Web API

Basitleştirilmiş bir Monolithic N-Tier Architecture, Product bacağının BaseRepository aracılığıya MongoDB kullandığı ve Basket bacağının Redis kullandığı ve Docker kapsayıcılarına dayanan örnek .NET 7 Web API uygulaması.

## Projede Kullanılan Teknolojiler/Araçlar

| Teknoloji |
| ------------- |
| .Net 7 |
| MongoDB | 
| Redis |
| FluentValidation | 
| Swagger |

## Kaynak olarak kullanılan hizmetler

```
Microsoft : https://learn.microsoft.com/tr-tr/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-7.0&tabs=visual-studio
MongoDB :  https://www.mongodb.com/docs/v2.6/tutorial/generate-test-data/
Nuget : https://www.nuget.org/
Medium makaleleri
```

## Projeyi Çalıştırmak

Eğer bilgisayarınızda [Docker](https://docs.docker.com/engine/install/) yok ise ilgili linkten kurulum adımlarını takip edip kurabilirsiniz. Akabinde projeyi ayağa kaldırmak için `docker-compose.yml` dosyasının bulunduğu dizine gelerek aşağıdaki komutları kullanmanız yeterli olacaktır.

Api => http://localhost:8000/swagger/index.html
Mongo Express => http://localhost:8081/

```powershell
Başlatmak için: 
    docker-compose build
    docker-compose up -d
Durdurmak için: 
    docker-compose down
```

## Öneri ve Tavsiyelerinize açığım

Benimle iletişime geçebilirsiniz. Sağlıcakla kalın :)
