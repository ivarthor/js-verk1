# js-verk1

1) null er ekkert og undefined er óskilgreint.

2) 'use strict' er sett efst í kóðann til að segja að það á að nota strict mode. Í strict mode er til dæmis ekki hægt að gera 
óskilgreindar breytur.

3) let er local, var er global, const er ekki hægt að breyta.

4) let x = 9;
   for (x >= 1) {
    console.log("hello" + x);
    x = x - 1;
   }
   
5) let x = 9;
   for (x >= 1) {
    console.log("hello" + x);
    x = x - 1;
   }
   
   let x
   for (x = 9; x >= 1; x--) {
    console.log("hello" + x);
   }
   
   for (let x = 9; x >= 1; x--) {
    console.log("Hello" + x);
   }
   
6) Hann býr til nafnlaust fall sem sendir alert með textanum 'Hello World', fyrsti sviginn lætur vita að þetta er function expression,
annar sviginn er sem þú geymir breyturnar fyrir föll í þessu tilviki eru engin, slaufusvigarnir er kóðinn sem er keyrður þegar það er keyrt fallið, síðasti sviginn keyrir fallið.

7)

8) var test = [12, 929, 11, 3, 199, 1000, 7, 1, 24, 37, 4,
    19, 300, 3775, 299, 36, 209, 148, 169, 299,
    6, 109, 20, 58, 139, 59, 3, 1, 139
];

test.forEach(function(tolur){
    if (tolur % 3 == 0){
        console.log(tolur + 100);
    }
    
    else {
        console.log(tolur)
    }
})

9) var bills = [50.23, 19.12, 34.01,
    100.11, 12.15, 9.90, 29.11, 12.99,
    10.00, 99.22, 102.20, 100.10, 6.77, 2.22
];

const totals = bills.map(x => x * 1.15);
console.log(totals)

10) x=(()=>x())()
