# Project-in-Node-
    file_r = open("input.txt", "r")
    splitted = file_r.read().split(',')

    alas_segitiga   	= list(map(int, splitted))
    tinggi_segitiga 	= list(map(int, splitted))
    sisi_segitiga_a 	= list(map(int, splitted))
    sisi_segitiga_b 	= list(map(int, splitted))
    sisi_segitiga_c 	= list(map(int, splitted))

    sisi_persegi 		= list(map(int, splitted))

    jari_jari_lingkaran	= list(map(int, splitted))

    luas_segitiga = (0.5 * alas_segitiga[0] * tinggi_segitiga[1])
    keliling_segitiga = (sisi_segitiga_a[2]+sisi_segitiga_b[3]+sisi_segitiga_c[4])

    luas_persegi = (2 * sisi_persegi[5])
    keliling_persegi = (4 * sisi_persegi[6])

    luas_lingkaran = (3.14 * (jari_jari_lingkaran[7] * 2))
    keliling_lingkaran = (2 * 3.14 * jari_jari_lingkaran[8])

    print("\n_____________________________________")
    print("Hasil Luas Segitiga 	 =" , luas_segitiga)
    print("Hasil Keliling Segitiga	 =" , keliling_segitiga)
    print("Hasil Luas Persegi 	 =" , luas_persegi)
    print("Hasil Keliling Persegi 	 =" , keliling_persegi)
    print("Hasil Luas Lingkaran 	 =" , luas_lingkaran)
    print("Hasil Keliling Lingkaran =" , keliling_lingkaran)
    print("_____________________________________")


