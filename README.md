PERTAMA


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../script/script.js"></script>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-[#324154] px-28 py-28">
    <div class="bg-[#597298] rounded-lg flex">
        <div class="w-8/12 flex flex-col items-center justify-center text-white text-[40px]">
            <h1>Masukan Kartu Anda</h1>
            <hr class="border-2 w-8/12 my-5">
            <h1>Please Insert Your Card</h1>
        </div>
        <div>
            <a href="./bahasa.html"><img src="../images/masukan-kartu.jpg" alt=""></a>
            
        </div>
    </div>
    
</body>
</html>



PILIH BAHASA

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../script/script.js"></script>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-[#324154] px-28 py-28">
    <div class="bg-[#597298] rounded-lg flex">
        <div class="w-10/12 flex flex-col justify-center text-white text-center text-4xl font-mono px-10 my-10 space-y-10">
            <div class="flex flex-col items-center space-y-5">
                <h1>Silahkan Pilih Bahasa Anda</h1>
                <hr class="border-2 w-[700px]">
                <h1>Please Select Your Language</h1>
            </div>
            <div class="space-y-5 text-2xl mr-[240px]">
                <div class="flex justify-end">
                    <a href="./pin.html">INDONESIA >></a>
                </div>
                <div class="flex justify-end cursor-pointer">
                    <p onclick="alert(`Fitur Ini Tidak Tersedia`)">INGGRIS >></p>
                </div>
                <div class="flex justify-end">
                    <a href="./index.html">CANCEL >></a>
                </div>
            </div>
            <div class="flex flex-col items-center space-y-5">
                <h1>To Obtain Card Press "CANCEL"</h1>
                <hr class="border-2 w-[700px]">
                <h1>Tekan "CANCEL" Untuk Membatalkan</h1>
            </div>
        </div>
        <div class="flex justify-center items-center">
            <img class="rounded-lg w-[80%]" src="../images/pilih-bahasa.png" alt="">
        </div>
    </div>
    
</body>
</html>




PIN

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-[#324154] px-28 py-10 h-[100vh] flex items-center justify-center">
    <div class="bg-[#597298] rounded-lg flex">
        <div class="w-8/12 flex flex-col items-center justify-center text-white text-center text-[25pt] font-mono px-10 gap-[20px]">
            <h1>Silahkan Masukan Pin Anda</h1>
            <div class="flex space-x-10">
                <input class="w-[250px] rounded-md text-center text-black" type="text" id="pin" placeholder="Masukan Pin">
               <button onclick="masuk()">ENTER >></button>
                <a href="./bahasa.html"><button class="text-red-600">CANCEL>></button></a>
                
            </div>
            <h1>Please Insert Your Pin</h1>
        </div>
        <img src="../images/masukan-pin.jpg" alt="">
    </div>


    <script src="../script/script.js"></script>
</body>
</html>



NOMINAL

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-[#324154] px-28 py-28 ">
    <div class="bg-[#597298] rounded-lg flex w-[150vh] ml-[150px] mt-[50px]">
        <div class="flex text-center flex-col mt-[60px] text-white font-bold text-[30px] gap-[50px] font-mono">
            <h1 class="text-[30pt] ml-[100px]">Silahkan Pilih Paket Nominal</h1>
            <div class="flex flex-row justify-center gap-[100px] ml-[100px]">
                <div class="flex flex-col gap-[20px] cursor-pointer">
                    <p onclick="tunai(cash.seratus)"><- 100.000</p>
                     <p onclick="tunai(cash.duaratus)"><- 200.000</p>
                      <p onclick="tunai(cash.tigaratus)"><- 300.000</p>
                       <p><- Nominal Lain</p>
                </div>
                <div class="flex flex-col gap-[20px] cursor-pointer">
                    <p onclick="tunai(cash.limaratus)">500.000 -></p>
                    <p onclick="tunai(cash.satujuta)">1.000.000 -></p>
                    <p onclick="tunai(cash.satusetengah)">1.500.000 -></p>
                    <p onclick="alert(`Fitur Tidak Tersedia`)">Transaksi -> Lain</p>
                </div>
            </div>
        </div>
        <img class="h-[600px] w-[500px] ml-[300px]" src="../images/ambil-uang.jpg" alt="">
    </div>


    <script src="../script/script.js"></script>
</body>
</html>


PECAHAN

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-[#324154] px-28 py-10 h-[100vh] flex items-center justify-center">
    <div class="bg-[#597298] rounded-lg flex">
        <div
            class="w-8/12 flex flex-col items-center justify-center text-white text-center text-[25pt] font-mono px-10 gap-[30px]">
            <h1>Masukan Pecahan 50.000 atau 100.000</h1>
            <div class="flex space-x-8">
                <input class="w-[300px] rounded-md text-center text-black" type="text" id="pecahan"
                    placeholder="MASUKAN PIN">
                <button onclick="pecah()">ENTER>></button>
                <a class="text-red-700" href="./nominal.html"><button>CANCEL>></button></a>
            </div>
            <h1>PECAHAN</h1>
        </div>
        <img src="../images/withdraw-money.jpg" alt="">
    </div>


    <script src="../script/script.js"></script>
</body>

</html>



SCRIPT

const input = document.getElementById('pin')
const pecah = document.getElementById('pecahan')

const pw = 123
let saldo = 10000000 //10jt

const cash = {
    seratus: 100000,
    duaratus: 200000,
    tigaratus: 300000,
    limaratus: 500000,
    satujuta: 1000000,
    satusetengah: 1500000,
}

function masuk(){
    if(input.value == pw){
        window.location.href = 'nominal.html'
    } else if(input.value == 0){
        alert('pin tidak boleh kosong')
    } else{
        alert('pin anda salah')
    }
}

function tunai(value){
    if(saldo >= value && confirm('anda akan menarik '+ value)== true){
        saldo = saldo - value
        alert(`anda akan menarik ${value} sisa saldo anda ${saldo}`)
    }
}

// 

function pecahan(value){
    if(pecah.value == 0){
        alert('silahkan masukan nominal')
    } else if(saldo < pecah.value){
        alert('saldo anda tidak mencukupi')
    } else if (pecah.value % 100000 == 0 || pecah.value % 50000 == 0){
        alert(`anda berhasil menarik saldo sebesar ${pecah.value}, sisa saldo anda ${saldo -= pecah.value}`)
    } else{
        alert('maaf pecahan tidak tersedia')
    }
}



// function pecahan(value){
//     if(saldo > pecahan.value){
//         if(pecah.value % 50000 == 0 || pecah.value % 100000 == 0) {
//             const popUp = confirm(`anda akan menarik sebesar ${pecahan.value} sisa saldo anda tersisa ${saldo - pecah.value}`)
//             if(popUp == true){
//                 window.location.href = 'index.html'
//             }
//         } else {
//             alert('pecahan tidak sesuai')
//         }
//     } else{
//         alert('saldo anda kurang')
//     }
// }


