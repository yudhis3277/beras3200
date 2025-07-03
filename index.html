<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard Modern</title>
    <!-- CSS Libraries -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css" rel="stylesheet">
    <link href="https://cdn.datatables.net/1.13.7/css/dataTables.bootstrap5.min.css" rel="stylesheet">
    <link href="https://cdn.datatables.net/buttons/2.4.2/css/buttons.bootstrap5.min.css" rel="stylesheet">
    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2ecc71;
            --bg-light: #f4f6f7;
            --bg-dark: #2c3e50;
            --text-dark: #333;
            --text-light: #f1f3f4;
        }
        body { background-color: var(--bg-light); color: var(--text-dark); transition: all 0.3s ease; }
        body.dark-mode { background-color: var(--bg-dark); color: var(--text-light); }
        body.blue-theme { --primary-color: #3498db; --secondary-color: #2980b9; }
        body.green-theme { --primary-color: #2ecc71; --secondary-color: #27ae60; }
        body.orange-theme { --primary-color: #e67e22; --secondary-color: #d35400; }
        .sticky-header { position: sticky; top: 0; z-index: 1000; background-color: white; box-shadow: 0 2px 4px rgba(0,0,0,0.1); transition: all 0.3s ease; }
        .dark-mode .sticky-header { background-color: var(--bg-dark); color: var(--text-light); }
        .metric-card { box-shadow: 0 6px 12px rgba(0,0,0,0.1); transition: transform 0.3s, box-shadow 0.3s; border-top: 4px solid var(--primary-color); }
        .metric-card:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(0,0,0,0.15); }
        .card-fixed-height { height: 450px; display: flex; flex-direction: column; }
        .card-fixed-height .card-body { flex: 1; overflow-y: auto; }
        .card-header { background-color: var(--primary-color); color: white; }
        .settings-menu { position: fixed; top: 15px; right: 15px; display: flex; align-items: center; gap: 15px; background-color: white; padding: 10px; border-radius: 30px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); z-index: 1100; transition: all 0.3s ease; }
        .dark-mode .settings-menu { background-color: var(--bg-dark); color: var(--text-light); }
        .settings-menu > i { cursor: pointer; transition: transform 0.2s, color 0.2s; font-size: 1.2rem; }
        .settings-menu > i:hover { transform: scale(1.2); }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-white sticky-header">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <img src="https://www.bps.go.id/_next/image?url=%2Fassets%2Flogo-bps.png&w=1080&q=75" alt="Logo BPS" style="max-height: 40px;">
            </a>
            <span class="navbar-text">
                <h5 class="mb-0">DASHBOARD MONITORING RATA-RATA HARGA BERAS DI TINGKAT PENGGILINGAN JAWA BARAT TAHUN 2025</h5>
            </span>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarContent" aria-controls="navbarContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarContent">
                <div class="navbar-nav ms-auto"></div>
            </div>
        </div>
    </nav>

    <div class="settings-menu">
        <i class="bi bi-moon-stars-fill" id="theme-toggle" title="Toggle Dark Mode"></i>
        <i class="bi bi-palette-fill theme-icon" data-theme="blue" title="Blue Theme" style="color:#3498db;"></i>
        <i class="bi bi-palette-fill theme-icon" data-theme="green" title="Green Theme" style="color:#2ecc71;"></i>
        <i class="bi bi-palette-fill theme-icon" data-theme="orange" title="Orange Theme" style="color:#e67e22;"></i>
    </div>

    <div class="container-fluid mt-4">
        <div class="row g-3 mb-3">
            <div class="col-md-4">
                <div class="card metric-card">
                    <div class="card-body">
                        <h5 class="card-title" id="latest-month-title">Rata-rata Harga Beras ...</h5>
                        <h2 id="overall-average-price">Rp 0/kg</h2>
                        <small class="text-success" id="latest-month-detail"><i class="bi bi-arrow-up"></i> Rata-rata Harga Beras ...</small>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card metric-card">
                    <div class="card-body">
                        <h5 class="card-title">Rata-rata Harga Beras Premium</h5>
                        <h2 id="premium-average-price">Rp 0/kg</h2>
                        <small class="text-info"><i class="bi bi-info-circle"></i> Kualitas Terbaik</small>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card metric-card">
                    <div class="card-body">
                        <h5 class="card-title">Rata-rata Harga Beras Medium</h5>
                        <h2 id="medium-average-price">Rp 0/kg</h2>
                        <small class="text-warning"><i class="bi bi-star-half"></i> Kualitas Menengah</small>
                    </div>
                </div>
            </div>
        </div>

        <div class="row g-3">
            <div class="col-md-4">
                <div class="card card-fixed-height">
                    <div class="card-header">Perkembangan Rata-rata Harga Beras</div>
                    <div class="card-body">
                        <table id="salesTable" class="table table-striped" style="width:100%">
                            <thead>
                                <tr>
                                    <th>No</th>
                                    <th>Bulan</th>
                                    <th>Premium</th>
                                    <th>Medium</th>
                                    <th>Rata-rata</th>
                                </tr>
                            </thead>
                            <tbody>
                                <!-- Data akan diisi oleh JavaScript -->
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card card-fixed-height">
                    <div class="card-header">Grafik Perkembangan Rata-rata Harga per Bulan</div>
                    <div class="card-body">
                        <canvas id="salesChart"></canvas>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card card-fixed-height">
                    <div class="card-header">Grafik Perkembangan Rata-rata Harga Menurut Kualitas</div>
                    <div class="card-body">
                        <canvas id="barChart"></canvas>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- JavaScript Libraries -->
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="https://cdn.datatables.net/1.13.7/js/jquery.dataTables.min.js"></script>
    <script src="https://cdn.datatables.net/1.13.7/js/dataTables.bootstrap5.min.js"></script>
    <script src="https://cdn.datatables.net/buttons/2.4.2/js/dataTables.buttons.min.js"></script>
    <script src="https://cdn.datatables.net/buttons/2.4.2/js/buttons.bootstrap5.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.1.53/pdfmake.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.1.53/vfs_fonts.js"></script>
    <script src="https://cdn.datatables.net/buttons/2.4.2/js/buttons.html5.min.js"></script>
    <!-- Papa Parse untuk parsing CSV -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/PapaParse/5.4.1/papaparse.min.js"></script>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // ===================================================================
            // KONFIGURASI
            // ===================================================================
            // GANTI URL INI dengan URL CSV dari Google Sheet Anda (dari Langkah 2)
            const googleSheetURL = 'https://docs.google.com/spreadsheets/d/e/2PACX-1vT5iFjVAUSunqDCttSh6XG_45IMpMvViwOLE1qz-OOjYy-RjDeu8jt6LbgZE15JbkJSSbgdcqQQM-i5/pub?gid=0&single=true&output=csv';

            // ===================================================================
            // INISIALISASI ELEMEN DASHBOARD
            // ===================================================================
            // Inisialisasi DataTable
            const salesTable = $('#salesTable').DataTable({
                columns: [
                    { title: 'No' }, { title: 'Bulan' }, { title: 'Harga Premium' }, { title: 'Harga Medium' }, { title: 'Rata-rata' }
                ],
                dom: 'Bfrtip',
                buttons: ['copy', 'csv', 'excel', 'pdf'],
                language: { search: "Cari:" },
                pageLength: 5,
            });

            // Inisialisasi Chart.js
            const initChart = (ctx, type, options) => new Chart(ctx, { type, data: { labels: [], datasets: [] }, options });

            const salesChartCtx = document.getElementById('salesChart').getContext('2d');
            const salesChart = initChart(salesChartCtx, 'line', getChartOptions('Grafik Perkembangan Harga per Bulan', 'Bulan', 'Harga (Rp)'));

            const barChartCtx = document.getElementById('barChart').getContext('2d');
            const barChart = initChart(barChartCtx, 'bar', getChartOptions('Perbandingan Harga per Bulan', 'Bulan', 'Harga (Rp)'));

            // Fungsi untuk membuat opsi chart
            function getChartOptions(titleText, xText, yText) {
                return {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: { legend: { position: 'bottom' } },
                    scales: {
                        x: { title: { display: true, text: xText } },
                        y: { title: { display: true, text: yText } }
                    }
                };
            }
            
            // ===================================================================
            // FUNGSI PENGAMBILAN DAN PEMROSESAN DATA
            // ===================================================================
            async function loadDashboardData() {
                try {
                    const response = await fetch(googleSheetURL);
                    if (!response.ok) throw new Error(`Network response was not ok: ${response.statusText}`);
                    const csvText = await response.text();
                    
                    Papa.parse(csvText, {
                        header: true,
                        dynamicTyping: true,
                        complete: (results) => {
                            processData(results.data);
                        },
                        error: (error) => {
                            console.error('Error parsing CSV:', error);
                            alert('Gagal memproses data dari Google Sheet.');
                        }
                    });
                } catch (error) {
                    console.error('Fetch error:', error);
                    alert('Gagal mengambil data dari Google Sheet. Periksa koneksi internet atau URL sheet.');
                }
            }

            function processData(data) {
                // Filter data yang valid (harga premium > 0)
                const validData = data.filter(row => row['Harga Premium'] && row['Harga Premium'] > 0);
                if (validData.length === 0) {
                    alert('Tidak ada data valid yang ditemukan di Google Sheet.');
                    return;
                }

                // Siapkan data untuk tabel dan chart
                const labels = [];
                const premiumPrices = [];
                const mediumPrices = [];
                const tableData = [];

                data.forEach(row => {
                    if(row.No && row.Bulan) { // Pastikan baris tidak kosong
                        const premium = row['Harga Premium'] || 0;
                        const medium = row['Harga Medium'] || 0;
                        const avg = (premium > 0 && medium > 0) ? ((premium + medium) / 2) : 0;
                        
                        labels.push(row.Bulan);
                        premiumPrices.push(premium);
                        mediumPrices.push(medium);
                        tableData.push([
                            row.No,
                            row.Bulan,
                            formatRupiah(premium),
                            formatRupiah(medium),
                            formatRupiah(avg)
                        ]);
                    }
                });

                // Dapatkan data bulan terakhir yang valid
                const latestData = validData[validData.length - 1];

                // Update semua komponen UI
                updateMetricCards(latestData, validData);
                updateDataTable(tableData);
                updateCharts(labels, premiumPrices, mediumPrices);
            }

            // ===================================================================
            // FUNGSI UNTUK UPDATE UI
            // ===================================================================
            const formatRupiah = (number) => {
                if(number === 0 || !number) return "Rp 0";
                return new Intl.NumberFormat('id-ID', { style: 'currency', currency: 'IDR', minimumFractionDigits: 0 }).format(number);
            };

            function updateMetricCards(latestData, allValidData) {
                const latestAvg = (latestData['Harga Premium'] + latestData['Harga Medium']) / 2;
                document.getElementById('latest-month-title').textContent = `Rata-rata Harga Beras ${latestData.Bulan} 2025`;
                document.getElementById('overall-average-price').textContent = `${formatRupiah(latestAvg)}/kg`;
                document.getElementById('latest-month-detail').innerHTML = `<i class="bi bi-arrow-up"></i> Data terbaru bulan ${latestData.Bulan}`;

                const totalPremium = allValidData.reduce((sum, row) => sum + row['Harga Premium'], 0);
                const totalMedium = allValidData.reduce((sum, row) => sum + row['Harga Medium'], 0);
                
                document.getElementById('premium-average-price').textContent = `${formatRupiah(totalPremium / allValidData.length)}/kg`;
                document.getElementById('medium-average-price').textContent = `${formatRupiah(totalMedium / allValidData.length)}/kg`;
            }

            function updateDataTable(data) {
                salesTable.clear().rows.add(data).draw();
            }

            function updateCharts(labels, premiumData, mediumData) {
                const chartData = {
                    labels: labels,
                    datasets: [{
                        label: 'Harga Premium',
                        data: premiumData,
                        borderColor: 'rgba(54, 162, 235, 1)',
                        backgroundColor: 'rgba(54, 162, 235, 0.6)',
                        fill: false,
                        tension: 0.1
                    }, {
                        label: 'Harga Medium',
                        data: mediumData,
                        borderColor: 'rgba(255, 99, 132, 1)',
                        backgroundColor: 'rgba(255, 99, 132, 0.6)',
                        fill: false,
                        tension: 0.1
                    }]
                };
                // Update Line Chart
                salesChart.data = chartData;
                salesChart.update();
                // Update Bar Chart
                barChart.data = chartData;
                barChart.update();
            }

            // ===================================================================
            // FUNGSI TEMA DAN EVENT LISTENERS
            // ===================================================================
            const themeToggle = document.getElementById('theme-toggle');
            themeToggle.addEventListener('click', () => {
                document.body.classList.toggle('dark-mode');
                // Update chart colors on theme change if needed
                loadDashboardData(); // Reload data to apply new chart colors if they are theme-dependent
            });

            const themeIcons = document.querySelectorAll('.settings-menu .theme-icon');
            themeIcons.forEach(icon => {
                icon.addEventListener('click', (e) => {
                    const theme = e.target.getAttribute('data-theme');
                    document.body.className = ''; // Clear all theme classes
                    document.body.classList.add(`${theme}-theme`);
                    updateThemeColors();
                });
            });

            function updateThemeColors() {
                const primaryColor = getComputedStyle(document.body).getPropertyValue('--primary-color');
                document.querySelectorAll('.card-header').forEach(card => card.style.backgroundColor = primaryColor);
                document.querySelectorAll('.metric-card').forEach(card => card.style.borderTopColor = primaryColor);
                // Force charts to re-render with new colors if styles are set via CSS variables
                if(salesChart) salesChart.update();
                if(barChart) barChart.update();
            }

            // ===================================================================
            // EKSEKUSI UTAMA
            // ===================================================================
            loadDashboardData();
            updateThemeColors(); // Apply initial theme
        });
    </script>
</body>
</html>
