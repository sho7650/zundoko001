String  Z = 'ズン';
String  D = 'ドコ';
String  K = 'キ・ヨ・シ！';
Integer R, i = 0;

List<String> ZD       = new List<String> {Z, D};
List<String> Complete = new List<String> {Z, Z, Z, Z, D};

do {
    R = Math.abs(Math.mod(Crypto.getRandomInteger(),2));
    System.debug(ZD[R]);
    
    if (Complete[i] == ZD[R])
        i++;
    else
        i = 0;
} while (i < 5);

System.debug(K);

