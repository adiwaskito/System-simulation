# Diagram Hubungan Komponen Sistem Transportasi

```mermaid
graph TD;
    A[Kendaraan] -->|Dikemudikan oleh| B[Pengemudi];
    B --> C[Rute];
    C --> D[Stasiun/Terminal];
    A --> E[Penumpang];
    E --> D;
    A --> F[Infrastruktur];
    F --> G[Sistem Manajemen Lalu Lintas];
    G --> A;
    C --> F;

### Langkah 3: Commit Perubahan

1. **Commit New File**:
   - Setelah menulis kode, tambahkan pesan commit di bagian bawah, misalnya `Add diagram.md with Mermaid diagram`.
   - Klik **Commit new file**.

### Langkah 4: Melihat Diagram di GitHub

1. **Buka File Markdown**:
   - Di dalam repositori, klik file `diagram.md` yang baru saja Anda buat.

2. **Lihat Rendering**:
   - GitHub akan merender kode Mermaid di dalam file markdown dan menampilkan diagram secara otomatis.

### Contoh Tampilan Kode Markdown dengan Mermaid di GitHub

```markdown
# Diagram Hubungan Komponen Sistem Transportasi

```mermaid
graph TD;
    A[Kendaraan] -->|Dikemudikan oleh| B[Pengemudi];
    B --> C[Rute];
    C --> D[Stasiun/Terminal];
    A --> E[Penumpang];
    E --> D;
    A --> F[Infrastruktur];
    F --> G[Sistem Manajemen Lalu Lintas];
    G --> A;
    C --> F;

### Kode Markdown Lengkap

Berikut adalah kode lengkap yang bisa Anda salin dan tempel di file `diagram.md` di GitHub:

```markdown
# Diagram Hubungan Komponen Sistem Transportasi

```mermaid
graph TD;
    A[Kendaraan] -->|Dikemudikan oleh| B[Pengemudi];
    B --> C[Rute];
    C --> D[Stasiun/Terminal];
    A --> E[Penumpang];
    E --> D;
    A --> F[Infrastruktur];
    F --> G[Sistem Manajemen Lalu Lintas];
    G --> A;
    C --> F;
