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
