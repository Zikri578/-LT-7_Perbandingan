# 7_Perbandingan

Operator perbandingan adalah simbol yang digunakan untuk membandingkan dua operand dan mengembalikan nilai boolean (true atau false) sesuai dengan hasil perbandingannya. Dalam JavaScript, terdapat beberapa operator perbandingan yang dapat digunakan, yaitu:

* Sama dengan (==): digunakan untuk membandingkan apakah dua operand sama dengan satu sama lain. Misalnya: 3 == 3 = true, 3 == 4 = false
* Tidak sama dengan (!=): digunakan untuk membandingkan apakah dua operand tidak sama dengan satu sama lain. Misalnya: 3 != 3 = false, 3 != 4 = true
* Lebih besar dari (): digunakan untuk membandingkan apakah operand kiri lebih besar dari operand kanan. Misalnya: 3 > 4 = false, 4 > 3 = true
* Lebih kecil dari (): digunakan untuk membandingkan apakah operand kiri lebih kecil dari operand kanan. Misalnya: 3 < 4 = true, 4 < 3 = false
* Lebih besar dari atau sama dengan (>=): digunakan untuk membandingkan apakah operand kiri lebih besar dari atau sama dengan operand kanan. Misalnya: 3 >= 4 = false, 4 >= 3 = true, 3 >= 3 = true
* Lebih kecil dari atau sama dengan (<=): digunakan untuk membandingkan apakah operand kiri lebih kecil dari atau sama dengan operand kanan. Misalnya: 3 <= 4 = true, 4 <= 3 = false, 3 <= 3 = true

Operator perbandingan juga dapat digunakan bersamaan dengan operator logika (&&, ||, !) untuk membuat pernyataan logika yang lebih kompleks. Misalnya:

    let x = 3;
    let y = 4;

    console.log(x > y && x != y); // Output: false
    console.log(x > y || x != y); // Output: true
    console.log(!(x > y)); // Output: true

