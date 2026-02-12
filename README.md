# Najma.html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabel Jadwal Pelajaran</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 50px;
        }

        h1 {
            margin-bottom: 20px;
        }

        table {
            border-collapse: collapse;
            width: 80%;
            max-width: 800px;
            text-align: center;
        }

        th, td {
            border: 1px solid black;
            padding: 15px;
            font-size: 18px;
        }

        /* Warna latar belakang untuk header */
        thead th {
            background-color: #e2e8f0; /* Abu-abu muda kebiruan */
        }

        /* Mengatur lebar kolom pertama agar lebih kecil */
        th:first-child, td:first-child {
            width: 20%;
        }
    </style>
</head>
<body>

    <h1>Jadwal Pelajaran Kelas X</h1>

    <table>
        <thead>
            <tr>
                <th>Hari</th>
                <th colspan="3">Mata Pelajaran</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Senin</td>
                <td>Informatika</td>
                <td>Matematika</td>
                <td>Bahasa Indonesia</td>
            </tr>
            <tr>
                <td>Selasa</td>
                <td>IPA</td>
                <td>IPS</td>
                <td>Bahasa Inggris</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
