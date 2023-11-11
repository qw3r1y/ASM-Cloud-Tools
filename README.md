#Cloud-Pentest-ASM-Tools



| Araçlar  | Açıklama |
| ------------- | ------------- |
| [Nimbostratus](https://github.com/andresriancho/nimbostratus)  | Bulduğumuz gizli anahtar (secret key) ve gizli erişim anahtarı (secret access key) setinin, kullanıcıya hangi yetkilere sahip olduğunu belirten bilgileri içermektedir. Ayrıca Metadata'ya erişime sahip olarak tüm kullanıcı bilgilerini çekebiliriz. Snapshot veya user gibi hassas işlemler yapabiliriz. |
| [DumpsterDiver](https://github.com/securing/DumpsterDiver)  | DumpsterDiver, anahtarlar (örneğin, AWS Erişim Anahtarı, Azure Share Key veya SSH anahtarları) veya parolalar gibi sabit kodlanmış sırları aramak için büyük hacimli verileri analiz edebilen bir araçtır. |
| [CloudBrute](https://github.com/0xsha/cloudbrute)  | CloudBrute, verilen anahtarlar veya URL'ler üzerinden brute force saldırıları gerçekleştirerek, bulut tabanlı hizmetlere ait varlıkları tespit etme amacını taşıyan bir araçtır.  |
| [Enumerate IAM](https://github.com/andresriancho/enumerate-iam)  | Bulduğumuz gizli anahtar (secret key) ve gizli erişim anahtarı (secret access key) setinin, kullanıcıya hangi yetkilere sahip olduğunu belirten bilgileri içermektedir.   |
| [S3 Fuzzer](https://github.com/pbnj/s3-fuzzer)  | S3 bucket bulma işlemlerinde kullanılan bir fuzzing aracı, Amazon Web Services (AWS) S3 hizmeti için belirli isim kalıplarını, olası kombinasyonları veya sık kullanılan terimleri kullanarak S3 bucket'ları keşfetmeye çalışır.  |
| [S3 Inspector](https://github.com/clario-tech/s3-inspector)  | AWS S3 bucketların izinlerini kontrol etmeye yönelik araçtır.  |
| [S3 Bucketeers](https://github.com/tomdev/teh_s3_bucketeers)  | Kendi bilgilerimizi veya hedefin bilgilerini girerek S3 bucketlar üzerinde pentest yapmamıza olanak sağlayan araçtır.  |
| [Bucket Stream](https://github.com/eth0izzle/bucket-stream)  | S3 bucketlarını bulup, bu bucketlardaki ilginç hareketlerin log kayıtlarını getirir. İlginç hareketler, erişimler, değişiklikler, silme işlemleri gibi olağan dışı olayları içerir. |
| [S3 Find](https://github.com/aaparmeggiani/s3find)  | Kullanıcını vermiş olduğu urle göre S3 bucket bulmayı sağlar.  |
| [Slurp](https://github.com/random-robbie/slurp)  | Verdiğimiz keyword , domain vb. gibi keywordlere uygun S3 Bucket bulmamızı sağlar.  |
| [AWS Bucket Dump ](https://github.com/jordanpotti/AWSBucketDump) | Kaba kuvvet saldırısı yöntemi ile S3 Bucket arar ve bu bucketların içerisinde hassas ve ilginç verileri tespit eder. |
| [S3Scanner](https://github.com/sa7mon/S3Scanner#quick-start)  | Belirtilen veya sağlanan isimlendirilmiş S3 bucketlarını ve diğer cloud araçlarını bularak listeler ve bunlar hakkında ayrıntılı bilgiler sunar. |
| [s3scan](https://github.com/bear/s3scan)  | S3 depolama alanı klasörlerinin ve bu klasörlere sahip kullanıcıların erişim haklarının bir dökümü oluşturur.  |
| [s3Finder](https://github.com/magisterquis/s3finder)  | Bir kelime listesi kullanarak veya sertifika şeffaflık günlüklerinden alan adları için certstream ağını izleyerek arama yapabilir. Bir ad noktalar içeriyorsa, noktaların yerini tirelerin aldığı bir ad da denenecektir. |
| [S3Scan](https://github.com/abhn/S3Scan)  | Verilen domain adına göre S3 bucketlarını bulur ve ardından bu bucketlara sahip kullanıcıların erişim haklarını göz önünde bulundurarak, okuma, yazma vb. izinlere göre bir liste oluşturur.  |
| [inSp3ctor](https://github.com/brianwarehime/inSp3ctor)  | Belirtilen veya sağlanan isimlendirilmiş S3 bucketları tespit eder.  |
| [AWS s3 Data Finder](https://github.com/Ucnt/aws-s3-data-finder)  | S3 bucketları kaba kuvvet yöntemi ile bularak bunların içerisindeki hassas verileri bulmamızı sağlar. |
| [Lazy S3](https://github.com/nahamsec/lazys3)  | Kaba kuvvet saldırı mantığını kullanarak S3 Bucketları tespit etmeye yarar. |
| [Bucket Scanner](https://github.com/securing/BucketScanner)  | S3 bucketları bulur ve buradaki izinler dosya türleri gibi yapıları da belirler.  |
| [Aws-Extender-Cli ](https://github.com/VirtueSecurity/aws-extender-cli) | AWS Extender CLI, boto/boto3 SDK kitaplığını kullanarak S3 paketlerinin yanı sıra Google Depolama paketlerini ve Azure Depolama kapsayıcılarını yaygın yanlış yapılandırma sorunları açısından test etmeye yönelik bir komut satırı betiğidir.  |
| [BucketCat](https://github.com/Atticuss/bucketcat)  | Sahibi tarafından gizlenmiş S3 bucketları hash yöntemi ile kullanarak bulmayı sağlar.  |
| [BucketLoot ](https://github.com/redhuntlabs/BucketLoot) | Belirtilen veya sağlanan anahtara göre S3 bucket içerisindeki dosyaları bularak listeler veya döndürür.  |
| [CloudFox](https://github.com/BishopFox/cloudfox)  | Vermiş olduğumuz key bilgilerini kullanarak birçok aracı test etmemizi sağlar.  |
| [Cred Scanner ](https://github.com/disruptops/cred_scanner) | Dosyalar üzerinde AWS kimlik bilgilerini bulmamızı sağlar.  |
| [CloudFrunt](https://github.com/MindPointGroup/cloudfrunt)  | Yanlış yapılandırılmış CloudFrount test etmemizi sağlar.  |
| [CloudJack](https://github.com/prevade/cloudjack)  | CloudJack, ayrılmış Route53 ve CloudFront yapılandırmalarının bir sonucu olarak AWS hesaplarını alt etki alanı ele geçirme güvenlik açıklarına karşı değerlendirir. |
| [DumpsterDiver](https://github.com/securing/DumpsterDiver)  | DumpsterDiver, anahtarlar (örneğin, AWS Erişim Anahtarı, Azure Share Key veya SSH anahtarları) veya parolalar gibi sabit kodlanmış sırları aramak için büyük hacimli verileri analiz edebilen bir araçtır.   |
| [Lambda Proxy ](https://github.com/puresec/lambda-proxy) | AWS Lambda ve SQLMAP kullanarak Sql Injection test etmemizi sağlar.  |
| [Barq](https://github.com/Voulnet/barq)  | EC2 makinelerine SSH bağlantımız olmadan saldırmamızı sağlar.  |
| [Cloud Brute](https://github.com/0xsha/cloudbrute)  | En iyi bulut sağlayıcılarında (Amazon, Google, Microsoft, DigitalOcean, Alibaba, Vultr, Linode) bir şirketin (hedef) altyapısını, dosyalarını ve uygulamalarını bulmaya yönelik bir araç.  |
| [Whispers](https://github.com/Skyscanner/whispers)  | Whispers, sabit kodlanmış kimlik bilgilerini ve tehlikeli işlevleri bulmak amacıyla çeşitli yaygın veri formatlarını ayrıştırmak için tasarlanmış bir statik kod analiz aracıdır.   |
| [Red Boto](https://github.com/ihamburglar/Redboto)  | AWS API'ye karşı test işlemlerini gerçekleştirmek için Python boto3 için Amazon SDK'yı kullanan bir komut dosyası koleksiyonudur.  |
| [Cfn_Nag](https://github.com/stelligent/cfn_nag)  | CFn-nag aracı, CloudFormation şablonlarında güvenli olmayan altyapıyı gösterebilecek kalıpları arar.   |
| [IAMFinder](https://github.com/prisma-cloud/IAMFinder)  | Hedef hesabın hangi izinlere sahip olduğunu gösterir.  |
| [Content Cell](https://github.com/cr0hn/festin#what-is-festin)  | S3 Bucketları bulmamızı sağlayan bir araçtır.  |
| [S3Insights](https://github.com/kurmiashish/S3Insights)  | S3 Bucketları analiz etmemizi sağlar.  |


