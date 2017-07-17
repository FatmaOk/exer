# exer
---
Purpose a study

`git log` komutu ile oluşturulan commitleri görebilirsiniz. Bu komutun çıktısı çok uzun olabilmektedir. Bu çıktıları daha kısa bir şekilde göstermek için `git log --oneline` kullanılabilir.

`git log` komutunun parametreleri:

1. --oneline: bütün commit kayıtlarını tek satır olarak gösterir
1. --decorate: branch'ları, etiketleri ve referans değerlerini renkli olarak gösterir
1. --graph: commit kayıtlarını grafiksel gösterir
1. --author-date-order: commit kayıtlarını tarih sırasına göre sıralar
1. --all: bütün commit kayıtlarını gösterir

Bütün parametreleri kullanmak istersek `log --oneline --all --author-date-order --decorate --graph`

Bu komutu her seferinde uzun uzun yazmak yerine `git logs` gibi kısa bir ifade ile yazmak istiyorsak aşağıdaki ayar yazır:

`git config --global alias.logs "log --oneline --all --author-date-order --decorate --graph"`

Burada belirtilen `logs` ifadesi yerine istediğimiz herhangi bir şey yazılabilir.

Artık bu komutu `git logs` yazarak kullanabiliriz.
