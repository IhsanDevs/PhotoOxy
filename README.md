
# PhotoOxy API

Konfigurasi PhotoOxy API untuk https://dbapi.org.


## Author

- [@IhsanDevs](https://www.github.com/IhsanDevs)


## Kontribusi

Data JSON ini adalah konfigurasi untuk API PhotoOxy pada website https://dbapi.org. Jika Anda ingin berkontribusi untuk gist ini, silahkan baca prosedur dibawah ini:
    
- key JSON `url` adalah URL PhotoOxy yang akan di scrapping. Harap tidak untuk memasukkan URL yang sama pada konfigurasi JSON ini.
- key JSON `name` adalah slug untuk API. Jadi gunakan smallcase dan underscore sebagai penghubung kata jika lebih dari 1.
- Key JSON `name` pada array `parameter` adalah key parameter yang akan menjadi isi dari body pada saat melakukan request pada API https://dbapi.org.
- Key JSON `image` pada array `parameter` digunakan untuk memberi tahu server API, jika value dari key name tag input pada PhotoOxy adalah berupa file gambar.
- Key JSON `input_name` pada array `parameter` adalah value `name` dari key pada tag input di website PhotoOxy. Jadi harap disesuaikan.