# Ling Ling

1. Mengunduh gambar, kemudian dapat dilihat bahwa gambar tersebut adalah meme dengan not balok Chopins Third Ballade. Dari soal dapat diketahui yang dicari adalah pembuat dari meme tersebut.
2. Untuk mendapatkan data tersebut dapat menggunakan exiftool dan grep pada terminal.

```
$ exiftool meme.png | grep Artist
```
3. Setelah itu akan muncul langsung Artist/pembuat dari meme tersebut.

## Flag

```
tjctf{ch0p1n_fl4gs}
```