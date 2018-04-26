---
title: "Steganografi: Bilgi Gizleme Sanatı"
categories:
  - Security
tags:
  - steganography
  - cryptography
last_modified_at: 2018-04-26T12:31:20-05:00
---
Steganografi, önemli bir bilginin çeşitli medya taşıyıcılarında gizlenmesi sanatıdır. Yıllar içerisinde bu alanda bir çok çalışma yapılmıştır. Teknolojinin gelişmeye devam etmesiyle, steganografinin ilk görüldüğü zamandan itibaren bir çok dijital taşıyıcıya veri gizlenebilmektedir.

![image-center]({{ '/images/steg.jpg' | absolute_url }}){: .align-center}

Tarihte steganografinin ilk görüldüğü yayın Alman bir Başkeşiş olan **Johannes Trithemius** tarafından _"Steganographia: hoe
est ars per occultam scripturam animi sui voluntatum absentibus aperiendi certa"_ adındaki yayınıdır. Bu bir üçlemedir ve ilk ikisinde steganografiden bahsetmektedir Trithemius. Üçlemenin sonuncusu ise astroloji ile ilgilidir. Trithemius, ruhlarla iletişime geçebilmek için böylesine yöntemleri konu alan bu yayınları çıkarmıştır.

Fakat günümüzde dogmatik yapılardan daha ziyade güvenlik amacı ile kullanılan steganografi; text tabanlı, image, audio ve video olmak üzere farklı dijital taşıyıcılar içerisinde tutulabilmektedir. Her bir taşıyıcı tipinde farklı metodlar ve yöntemler kullanılabilmektedir. Kimi zaman bir yöntem yetersiz olabilmekte ve bu algoritmayı daha geliştirme gereksinimi duyulmaktadır. 

## Peki neden kriptografi başlı başına yetersizdir (aynı soru steganografi içinde sorulabilmektedir)?

Kriptolojinin kaygısı mesajın içeriğinin gizlenmesidir. Dolayısı ile gizlenen yana şifrelenen mesaj gözle görülebilir ve şifrelendiği algılanabilmektedir. Steganografinin amacı ise ortada bir mesaj yokmuş imajı oluşturmaktır. Bu durumda bir şifreleme işlemi yapılmamakta fakat çeşitli taşıyıcılar kullanılarak mesajın iletilmesi için güvenli bir kanal oluşturulmaya çalışılmaktadır.

## Steganografinin bazı yöntemleri;
  * Image Steganografi
      * LSB (Least Significant Bit) yöntemi
      * Maskeleme ve Filtreleme
      * Redundant Pattern Encoding
      * Encrypt and Scatter
      * Algorithms and transformations
  * Audio Steganografi
      * LSB kodlama
      * Parity kodlama
      * Faz kodlama
      * Dağıtık spektrum
      * Eko gizleme
  * Video Steganografi
      * LSB yerleştirme
      * Gerçek zamanlı steganografi
