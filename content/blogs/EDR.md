---
title: "Endpoint Detection and Response Nedir ve Nasıl Çalışır?"
date: 2024-07-02T14:00:33+05:30
draft: false
author: "Özcan Işık"
tags:
  - EDR
image: /images/blogs/EDR/security.jpg
description: ""
toc: true
---

<a href="https://www.freepik.com/free-vector/data-protection-background-vector-cyber-security-technology-purple-tone_18236485.htm#query=Data%20security%20technology%20background%20vector%20in%20blue%20tone&position=1&from_view=author&uuid=129bfa8b-6fa0-4766-b132-8d5bfe13caba">Image by rawpixel.com</a> on Freepik

## Endpoint Detection and Response Nedir?

Günümüzde, siber güvenlik, dijital dönüşümün getirdiği kolaylıklarla birlikte gelen riskleri yönetmek için hayati bir öneme sahiptir. Siber tehditler, her geçen gün daha karmaşık hale gelmekte ve veri ihlalleri, kimlik hırsızlığı, maddi ve manevi kayıplar gibi zararlarla sonuçlanabilmektedir. Bu yüzden, siber güvenlik önlemleri artık bir seçenek değil, zorunluluk haline gelmiştir. Siber tehditlerin önlenmesi ve tespit edilmesi amacı ile güvenlik duvarları, SIEM ve SOAR sistemleri, NTA (Network Traffic Analysis) araçları, antivirüs yazılımları gibi pek çok güvenlik aracı bir arada çalışmaktadır. Bu yazıda Uç Nokta Algılama ve Yanıt (EDR) sistemleri üzerine konuşacağız.

Fakat nedir bu uç nokta (Endpoint) veya uç cihaz kavramı ilk olarak buna bir açıklık getirelim. Uç cihazlar kullanıcıların ağa erişim sağladıkları son noktalar olarak kabul edilir ve genellikle veri iletiminin başlangıç veya bitiş noktalarıdır. Bu cihazlara örnek olarak;

- Masaüstü ve Dizüstü Bilgisayarlar
- Mobil Cihazlar
- Tabletler
- Sunucular
- Dijital Yazıcılar
- Medikal Cihazlar
- Akıllı Sistemler
- IOT Cihazları
- POS Cihazları

verilebilir. Görüldüğü üzere bu cihazlar günlük hayatımızda ve iş yaşantımızda sürekli olarak karşımıza çıkan ve aktif olarak doğrudan iletişim halinde olduğumuz yapılardır. Saldırganlar, oltalama (phising), fidye yazılımları, dosyasız zararlı yazılımlar (fileless malware), servis dışı bırakma saldırıları (DoS) gibi pek çok farklı saldırı türü ile uç cihazları hedef almaktadır. Bu sebeple bu noktalardaki güvenlik önlemleri siber tehditlere karşı korunma stratejisinin temel bir parçasıdır. Bu bağlamda da EDR çözümleri karşımıza çıkmaktadır.

2013'te **Gartner**'dan Anton Chuvakin, bilgisayarlar ve diğer uç cihazlardaki şüpheli faaliyetleri ve bu faaliyetlerin izlerini bulup incelemeye odaklanan araçlar için "EDR" terimini kullandı. Bu yapı temel olarak antivirüslerin atlatılabilir olmasından kaynaklı ortaya çıkmıştır. O yıllarda ağ cihazları hariç kullanıcıların davranışlarını yakalayabilen bir uç nokta yönetim modülü bulunmamaktaydı. Bu sebeple özellikle vaka analistlerinin geçmişe yönelik adli (forensic) verisi toplayabilmesi amacıyla bu teknoloji hayata geçmiştir. 

EDR, uç cihazların detaylı bir şekilde izlenebilmesine olanak tanır. Bu araç, tehditlerin nereden geldiğini ve nasıl ortaya çıktığını, uç noktalarda kullanıcıların hangi süreç ve aktiviteleri gerçekleştirdiğini, internet üzerinde yapılan aktiviteleri ve hangi uygulamaların indirildiğini, diskte hangi verilerin tutulduğunu ve hafızada nelerin olduğunu gibi aklımıza gelebilecek verinin olduğu her türlü yerdeki verileri toplar ve anlamlı loglar üretmeye çalışır. Kısaca EDR, gelişmiş algoritmalarla birlikte kullanıcı davranışlarını analiz edip şüpheli davranışları adresler ve belirlenen tehditlere otomatik olarak yanıtlar verir.

İleri seviye antivirüsler ile ciddi gelişmeler yaşanmış olsa da geleneksel antivirüsler imza tabanlı bir yaklaşım sergileyerek zararlı yazılımları tespit etmeyi amaçlamaktaydı. Ancak son yıllarda karşımıza çıkan **"Zero Day"** kavramı ve **dosyasız zararlı yazılımlar** ile beraber geleneksel antivirüsler saldırganlar tarafından kolayca atlatılabilmektedir. Bu noktada EDR çözümleri, makine öğrenimi ve davranışların analizi ile beraber olayları ilişkilendirerek gelişmiş bir koruma sağlar. EDR' nin bazı önemli özelliklerine yakından bakacak olursak:

1. **Görünürlük (Visibility):** EDR, **gerçek zamanlı** çalışarak aktiviteleri yakalayıp kısa süre içerisinde vaka analistlerine yönlendirir.
2. **Tespit:** Önceden tanımlı davranış kalıpları ve yapay zeka teknolojilerini kullanarak şüpheli aktiviteleri hızla tespit eder. Bu, tehditlerin erkenden fark edilip müdahale edilmesini sağlar.
3. **Tehdit Avcılığı**: Sistemlerdeki anomalileri ve önceden belirlenmemiş tehditleri proaktif bir şekilde tespit etmeye, incelemeye ve müdahale etmeye yardımcı olur.
4. **Hızlı Cevap Verme:** EDR'nin en önemli özelliklerinden biridir. Özellikle EPP (Endpoint Protection Platform) ile beraber çalışarak olaylara hızlıca müdahale etme yeteneği sayesinde olası bir tehditin **yanal hareket (lateral movement)** ile diğer bölgelere sıçramasının önüne geçer.
5. **Uyarı Sistemi:** EDR, davranışsal analizlerin yapılabildiği ve değişikliklerin olduğu önemli logları toplar ve bunlara bağlı olarak uyarılar üretir.

Toparlayacak olursak Endpoint Detection and Response (EDR), bilgisayarlar, tabletler, sunucular gibi uç cihazlardaki tehditleri gerçek zamanlı tespit etmek için davranışsal analiz ve makine öğrenimi tekniklerini kullanır. Sistemdeki aktiviteleri analiz eder ve bir çok farklı veriyi toplar. Bir tehdit tespit ettiğinde hızlıca aksiyon alabilir ve analistlere uyarı verebilir. Ayrıca geçmişteki tehditlerin ve saldırıların incelenmesi amacı ile de kullanılabilir.

Sektörde popüler EDR çözümleri arasında **CrowdStrike Falcon**, **VMware Carbon Black EDR**, **ThreatDown EDR** ve **Malwarebytes EDR** gibi ürünler ön plana çıkmaktadır.

## Endpoint Detection and Response Nasıl Çalışır?

![edr-steps](/images/blogs/EDR/edr-steps.png "EDR Steps")

EDR sistemleri, izlenen her uç cihazda çalışan ajanlara sahiptir. Bu ajanlar, cihazdaki faaliyetleri sürekli olarak izler ve bu verileri merkezi bir sunucuya veya bulut tabanlı bir platforma gönderir. Ajanlar, sistem kaynaklarından çeşitli bilgileri (örneğin, işlemci kullanımı, ağ trafiği, dosya sistemi değişiklikleri, kayıt defteri etkinlikleri, hafızadaki veriler) toplar. 

Toplanan verileri, önceden tanımlanmış tehdit imzaları, davranış kuralları ve yapay zeka/makine öğrenimi algoritmaları kullanarak analiz eder. Anormal veya şüpheli aktiviteler, bu analiz süreçleri sonucunda belirlenir. Örneğin, bilinen bir zararlı yazılımın imzası tespit edilebilir veya bir kullanıcının normalden sapma gösteren davranışları EDR tarafından yakalanabilir. 

Tehdit tespit edildiğinde, EDR sistemi otomatik olarak yanıt verebilir veya SOC ekibine uyarı gönderebilir. Yanıtlar, şüpheli uygulamaları durdurma, zararlı dosyaları karantinaya alma veya cihazı ağdan izole etme gibi eylemleri içerebilir. Bu da daha fazla zararın önlenmesine yardımcı olur. 

SOC ekipleri, EDR sisteminin sağladığı detaylı bilgiler ve uyarılar sayesinde olaylara hızlı bir şekilde yanıt verebilir. EDR, olaylarla ilgili kapsamlı bilgiler sağlayarak soruşturma süreçlerini destekler ve tehdit avcılığı faaliyetlerini kolaylaştırır. Ayrıca, olası bir saldırı sonrasında geriye dönük analiz yapma imkanı sunar. Bu, saldırının detaylarını ve kapsamını anlamak için çok önemlidir ve güvenlik önlemlerinin sonradan iyileştirilmesine olanak tanır.

Günümüzde maalesef yalnızca EDR araçları güvenlik için yeterli değildir ve bu araçlarla beraber **EPP, SIEM, SOAR, NTA, Yeni Nesil Antivirüsler, Güvenlik Duvarları** gibi pek çok yapı beraber çalışmak zorundadır. Özellikle son yıllarda **XDR** gibi EDR çözümünden daha kapsamlı yapılar gittikçe ön plana çıkmaktadır. Fakat o başka bir yazının konusu...


