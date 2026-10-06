-- ============================================
-- DATABASE SISTEM PENJUALAN TOKO SEDERHANA
-- ============================================

CREATE DATABASE IF NOT EXISTS toko_jaya;

USE toko_jaya;


-- ============================================
-- 1. TABEL PELANGGAN
-- ============================================

CREATE TABLE IF NOT EXISTS pelanggan (
    id_pelanggan INT PRIMARY KEY,
    nama_pelanggan VARCHAR(100) NOT NULL,
    alamat VARCHAR(200),
    no_hp VARCHAR(20)
);


-- ============================================
-- 2. TABEL PRODUK
-- ============================================

CREATE TABLE IF NOT EXISTS produk (
    id_produk INT PRIMARY KEY,
    nama_produk VARCHAR(100) NOT NULL,
    kategori VARCHAR(50),
    harga DECIMAL(12,2) NOT NULL,
    stok INT NOT NULL
);


-- ============================================
-- 3. TABEL TRANSAKSI
-- ============================================

CREATE TABLE IF NOT EXISTS transaksi (
    id_transaksi INT PRIMARY KEY,
    id_pelanggan INT NOT NULL,
    tanggal_transaksi DATE NOT NULL,
    total_harga DECIMAL(12,2) NOT NULL,
    metode_pembayaran VARCHAR(30),

    FOREIGN KEY (id_pelanggan)
        REFERENCES pelanggan(id_pelanggan)
);


-- ============================================
-- 4. TABEL DETAIL TRANSAKSI
-- ============================================

CREATE TABLE IF NOT EXISTS detail_transaksi (
    id_detail INT PRIMARY KEY,
    id_transaksi INT NOT NULL,
    id_produk INT NOT NULL,
    jumlah INT NOT NULL,
    harga DECIMAL(12,2) NOT NULL,
    subtotal DECIMAL(12,2) NOT NULL,

    FOREIGN KEY (id_transaksi)
        REFERENCES transaksi(id_transaksi),

    FOREIGN KEY (id_produk)
        REFERENCES produk(id_produk)
);


-- ============================================
-- DATA PELANGGAN
-- ============================================

INSERT INTO pelanggan VALUES
(1, 'Andi', 'Jl. Merdeka No. 1', '081234567801'),
(2, 'Budi', 'Jl. Mawar No. 2', '081234567802'),
(3, 'Citra', 'Jl. Melati No. 3', '081234567803'),
(4, 'Deni', 'Jl. Kenanga No. 4', '081234567804'),
(5, 'Eka', 'Jl. Dahlia No. 5', '081234567805'),
(6, 'Fajar', 'Jl. Anggrek No. 6', '081234567806'),
(7, 'Gita', 'Jl. Flamboyan No. 7', '081234567807'),
(8, 'Hadi', 'Jl. Kamboja No. 8', '081234567808'),
(9, 'Intan', 'Jl. Teratai No. 9', '081234567809'),
(10, 'Joko', 'Jl. Tulip No. 10', '081234567810');


-- ============================================
-- DATA PRODUK
-- ============================================

INSERT INTO produk VALUES
(1, 'Indomie Goreng', 'Makanan', 3500, 100),
(2, 'Indomie Kuah', 'Makanan', 3500, 100),
(3, 'Beras 5 Kg', 'Sembako', 75000, 30),
(4, 'Gula 1 Kg', 'Sembako', 16000, 50),
(5, 'Minyak Goreng 1L', 'Sembako', 18000, 40),
(6, 'Teh Celup', 'Minuman', 8000, 60),
(7, 'Kopi Sachet', 'Minuman', 2500, 100),
(8, 'Air Mineral', 'Minuman', 4000, 100),
(9, 'Sabun Mandi', 'Kebutuhan', 5000, 50),
(10, 'Pasta Gigi', 'Kebutuhan', 12000, 40);


-- ============================================
-- DATA TRANSAKSI
-- ============================================

INSERT INTO transaksi VALUES
(1, 1, '2026-09-01', 35000, 'Cash'),
(2, 2, '2026-09-02', 75000, 'Cash'),
(3, 3, '2026-09-03', 32000, 'QRIS'),
(4, 4, '2026-09-04', 18000, 'Cash'),
(5, 5, '2026-09-05', 32000, 'QRIS'),
(6, 6, '2026-09-06', 25000, 'Cash'),
(7, 7, '2026-09-07', 40000, 'QRIS'),
(8, 8, '2026-09-08', 20000, 'Cash'),
(9, 9, '2026-09-09', 60000, 'QRIS'),
(10, 10, '2026-09-10', 36000, 'Cash');


-- ============================================
-- DATA DETAIL TRANSAKSI
-- ============================================

INSERT INTO detail_transaksi VALUES
(1, 1, 1, 10, 3500, 35000),
(2, 2, 3, 1, 75000, 75000),
(3, 3, 4, 2, 16000, 32000),
(4, 4, 5, 1, 18000, 18000),
(5, 5, 6, 4, 8000, 32000),
(6, 6, 7, 10, 2500, 25000),
(7, 7, 8, 10, 4000, 40000),
(8, 8, 9, 4, 5000, 20000),
(9, 9, 10, 5, 12000, 60000),
(10, 10, 5, 2, 18000, 36000);


-- ============================================
-- CEK DATA
-- ============================================

SELECT * FROM pelanggan;

SELECT * FROM produk;

SELECT * FROM transaksi;

SELECT * FROM detail_transaksi;