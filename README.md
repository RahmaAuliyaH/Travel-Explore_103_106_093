# Travel-Explore_103_106_093
NAMA ANGOTA KELOMPOK:
1. M. MAULANA MUSAFIR (093)
2. RAHMA AULIYA HASANAH (103)
3. AHMAD FAIZUL ABID F. (106)

MENJAWAB PERTANYAAN SAAT PRESENTAS:
1. Memasukkan Image ke Android Studio dengan mengcopy paste image ke dalam folder res/drawble/bromo.jpg (contoh). Untuk menampilkan image di dalam Android Studionya menggunakan script : imageRes = R.drawable.kidungtenggerdance 
Saat melakukan uji coba dengan memberi spasi pada nama file image, terjadi error (sudah di coba di depan saat presentasi)
2. Menambahkan Preview di File ExploreScreen.kt dengan mengcopy paste script Preview di file HomeScreen.kt dan disesuaikan menjadi seperti: @Preview(showBackground = true)
@Composable
fun ExploreScreenPreview() {
    MaterialTheme {
        ExploreScreen()}}
Lalu mengganti ukuran image Kidung dengan script awal gridHeight = 230.dp untuk menentukan ukuran grid card dimenu explore menjadi  gridHeight = 320.dp untuk menentukan ukuran grid card dimenu explore hasilnya gambar jadi lebih panjang ke bawah saat di Preview (sudah di tunjukkan di depan saat presentasi)
3. Mengganti nama icon di Navbar sat mode tab, jadi cara untuk mengganti nama icon di navbar di file AppNavigation.kt, pada file ini berisi 3 bagian yaitu: enum class AppTab(daftar menu, yaitu nama dan ikon nya), FloatingNav(tampilan footer melayang di HP potrait, SideRail: tampilan menu samping pada layar lebar/tab. karena FloatingNav dan SideRail sama sama membaca daftar dari AppTab, jadinya itu cukup untuk mengubah satu tempat. lalu untuk mengubah nama dan icon menu itu pada script : enum class AppTab(val label: String, val icon:
   ImageVector) {
    Home("Home", Icons.Rounded.Home),
    Explore("Explore", Icons.Rounded.Explore),
    Booking("Booking", Icons.Rounded.CalendarMonth),
    Settings("Settings", Icons.Rounded.Settings),
}
pada script tersebut diganti saja salah satu pada nama icon nya, tadi pada saat presentasi kita mengubah pada nama ikon home menjadi beranda.
