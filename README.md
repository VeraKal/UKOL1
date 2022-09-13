
Než jsem odevzdávala, přišlo mi zbytečně zdvojené mé původní:

.hlavicka,
.paticka {
    padding: 15px 10%;
}

section {
    padding: 0 10%;
}

Chtěla jsem ho sjednotit na

header,
section,
footer {
    padding: 15px 10%;
}

ale to mi pak obrázky vedle h2 vyskočí nad nadpisy a nejsem schopná domyslet proč tam to padding v section vadí, když mají obrázky nastaveno obtékání :) To padding, margin a pozicování se asi bude ještě řešit v dalším týdnu, tak třeba na to přijdu... 