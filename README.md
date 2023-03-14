PERTAMA


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-blue-900 px-28 py-28">
    <div class=" bg-gray-500 rounded-lg flex">
        <div class="w-8/12 justify-end flex flex-col justify-center items-center text-[32pt] text-white font-mono ">
            <h1>Silahkan Masukan Kartu Anda</h1>
            <hr class="border-2 w-8/12 my-5">
            <h1>Please Insert Your Pin</h1>
        </div>
        <div>
            <a class="" href="bahasa.html"><img src="../images/masukan-kartu.jpg" alt=""></a>

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
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-blue-900 px-28 py-28">
    <div class=" bg-gray-600 rounded-lg flex">
        <div
            class="text-white font-mono w-8/12 flex flex-col justify-center text-center text-4xl my-10 px-10 space-y-10">
            <div class="flex flex-col items-center space-y-5">
                <p>Silahkan Pilih Bahasa Anda</p>
                <hr class="border-2 w-[700px]">
                <p>Please Select Your Language</p>
            </div>
            <div class="text-3xl ml-[550px] space-y-5 cursor-pointer">
                <a href="pin.html">
                    <p>INDONESIA >></p>
                </a>
                <p onclick="alert(`Fitur Ini Tidak Tersedia! - Feature Not Available`)">INGGRIS >></p>
                <a href="index.html">
                    <p class="mt-[20px] text-red-500">CANCEL >></p>
                </a>

            </div>
            <div class="flex flex-col items-center space-y-5">
                <p>To Obtain Card Press "CANCEL"</p>
                <hr class="border-2 w-[700px]">
                <p>Tekan "CANCEL" Untuk Membatalkan</p>
            </div>
        </div>
        <div>
            <img src="../images/pilih-bahasa.png" alt="">
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

<body class="bg-blue-900 px-28 py-28">
    <div class="bg-gray-600 rounded-lg flex">
        <div class="w-8/12 text-white flex justify-center items-center flex-col gap-[20px] text-[32pt] font-mono">
            <h1>Silahkan Masukan Pin Anda</h1>
            <div>
                <input class="text-black" type="password" id="pin">
                <button onclick="masuk()">ENTER>></button>
                <a href="bahasa.html"><button class="text-red-500">CANCEL>></button></a>
            </div>
            <h1>Tekan "CANCEL" Untuk Membatalkan</h1>
        </div>
        <img class="rounded-r-lg" src="../images/masukan-pin.jpg" alt="">
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

<body class="bg-blue-900 px-28 py-28">
    <div class="bg-gray-600 rounded-lg flex">
        <div class="w-8/12 text-white flex justify-center items-center flex-col text-[23pt] gap-[50px] font-mono">
            <h1 class="space-y-5 text-5xl">Silahkan Pilih Paket Nominal</h1>
            <div class="flex flex-row gap-[100px] cursor-pointer">
                <div class="space-y-5">
                    <p onclick="tunai(cash.seratus)">
                        <- 100.000</p>
                            <p onclick="tunai(cash.duaratus)">
                                <- 200.000</p>
                                    <p onclick="tunai(cash.tigaratus)">
                                        <- 300.000</p>
                                        <a  href="pecahan.html"><p class="mt-[20px]">
                                            <- Nominal Lain</p></a>
                                            
                </div>
                <div class="space-y-5">
                    <p onclick="tunai(cash.limaratus)">500.000 -></p>
                    <p onclick="tunai(cash.satujuta)">1.000.000 -></p>
                    <p onclick="tunai(cash.satujutasetengah)">1.500.000 -></p>
                    <p onclick="alert(`Fitur Tidak Tersedia!`)">Transaksi Lain -></p>
                </div>
            </div>
        </div>
        <img class="rounded-r-lg" src="../images/withdraw-money.jpg" alt="">
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

<body class="bg-blue-900 px-28 py-28">
    <div class="bg-gray-600 rounded-lg flex">
        <div class="w-8/12 text-white flex justify-center items-center flex-col gap-[20px] text-[32pt] font-mono">
            <h1 class="flex text-center">Masukan Jumlah Nominal Pecahan 100.000 dan 50.000</h1>
            <div>
                <input class="text-black" type="text" id="pecahan">
                <button class="text-green-500" onclick="pecahan()">ENTER>></button>
                <a href="nominal.html"><button class="text-red-500">CANCEL>></button></a>
            </div>
            <h1>Tekan "CANCEL" Untuk Membatalkan</h1>
        </div>
        <img class="rounded-r-lg" src="../images/withdraw-money.jpg " alt="">
    </div>

    <script src="../script/script.js"></script>
</body>

</html>



SCRIPT

const input = document.getElementById('pin')
const pecah = document.getElementById('pecahan')

const pw = 123
let saldo = 1000000 //1jt

const cash = {
    seratus: 100000,
     duaratus: 200000,
      tigaratus: 300000,
       limaratus: 500000,
        satujuta: 1000000,
         satujutasetengah: 1500000,
}

function masuk(){
    if(input.value == pw){
        window.location.href = 'nominal.html'
        alert('Login Berhasil')
    } else if(input.value.length == 0){
        alert('Pin Tidak Boleh Kosong')
    } else{
        alert('Pin Salah')
    }
}

function tunai(value){
    if(saldo >= value && confirm('yakin anda akan menarik sebesar '+ value)== true){
        saldo = saldo - value
        window.location.href = 'index.html'
        alert(`anda menarik sebesar ${value} sisa saldo anda ${saldo}`)
    } else if(saldo < value){
        alert('Saldo Anda Tidak Cukup')
    }
}

function pecahan (value){
    if(pecah.value == 0){
        alert('Masukan Nominal Anda')
    } else if(saldo < pecah.value){
        alert('Saldo Anda Tidak Cukup')
    } else if(pecah.value % 50000 == 0){
        alert(`anda akan menarik sebesar ${pecah.value} sisa saldo anda sebesar ${saldo -= pecah.value}`)
        window.location.href = 'ambilkartu.html'
    } else{
        alert('Pecahan Tidak Tersedia')
    }
}


