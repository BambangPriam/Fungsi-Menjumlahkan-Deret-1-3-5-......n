# Fungsi-Menjumlahkan-Deret-1-3-5-......n
    #include<stdio.h>
    long int deret (int x);
    main()
    {
    int N;
    long int hasil;
    printf("Program Menghitung Deret 1+3+5+7+....\n");
    printf("Masukkan nilai akhir deret: ");
    scanf("%d",&N);
    hasil=deret(N);
    printf("\n Nilai hasil penjumlahan deret= %d", hasil);
    }
    long int deret(int x)
    {
        int i;
        long int z =0;
        printf("Nilai i: ");
        for (i=1; i<=x; i=i+2)
        {
            z+=i;
            printf("\n %d", i);
        }
        return (z);
    }
   ![img](https://raw.githubusercontent.com/BambangPriam/Fungsi-Menjumlahkan-Deret-1-3-5-......n/master/Fungsi%20Menjumlahkan%20Deret%201%2B3%2B5%2B....n.png)
