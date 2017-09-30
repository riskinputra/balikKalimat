# Membalikkan Kalimat
Latihan 3 - Program untuk Membalikkan Kalimat.

Terdapat sebuah function balikKalimat(kalimat) dengan parameter kalimat. Function akan me-return parameter kalimat dengan tampilan huruf yang terbalik.

## Code
```
function balikKalimat(kalimat) {
  /*
    Pertama kita pisahkan perhuruf dengan split(), lalu balik setiap hurufnya dengan reverse(), Kemudian di gabungkan kembali       dengan join
  */
  return kalimat.split('').reverse().join('');

}

console.log(balikKalimat('Super Hero'));
console.log(balikKalimat('John Doe'));
console.log(balikKalimat('I am a bookworm'));
console.log(balikKalimat('Coding is my hobby'));
console.log(balikKalimat('Hungry'));

```
