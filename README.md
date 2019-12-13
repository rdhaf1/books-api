Books API adalah RESTful Webservice Api palsu yang dibuat menggunakan server My JSON Server. RESTful Api palsu merupakan API yang dibuat dengan server yang sudah tersedia dan sumber data yang statis (bukan dari database). Sehingga data yang di simpan, ubah atau hapus pada RESTful Api hanya akan bertahan dalam periode waktu tertentu.

    baseUrl : https://my-json-server.typicode.com/rdhaf1/books-api

Berikut adalah beberapa aksi HTTP yang dapat kamu lakukan dengan API ini:

    GET ALL

    endpoint: ${baseUrl}/books

    GET ONE

    endpoint: ${baseUrl}/books/${id}

    POST

    endpoint: ${baseUrl}/books

    PUT

    endpoint: ${baseUrl}/books/${id}

    PATCH

    endpoint: ${baseUrl}/books/${id}

    DELETE

    endpoint: ${baseUrl}/books/${id}
