## Membuat project baru :

`rails new <nama-project>`

Contoh : `rails new perpustakaan`

## Membuat project baru khusus API tanpa assets :

`rails new <nama-project> --api --no-sprockets`

Contoh : `rails new perpustakaan --api --no-sprockets`

## Membuat project baru khusus API dengan database yang ditentukan :

`rails new <nama-project> --api --no-sprockets -d <jenisdatabase>`

Contoh : `rails new perpustakaan --api --no-sprockets -d postgresql`

## Membuat model database :

`rails g model <nama-model>`

Contoh : `rails g model buku`

## Membuat model database beserta field :

`rails g model <nama-model> [field[:type][:index] field[:type][:index]]`

Contoh : `rails g model buku judul:string penerbit:string tahunTerbit:integer`