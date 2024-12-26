# Didik-Purnomo
Binance
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laporan Harian</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Laporan Harian Anggota</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#balance">Laporan Balance</a></li>
            <li><a href="#profit">Profit Harian</a></li>
            <li><a href="#transaction">Deposit & Withdrawal</a></li>
        </ul>
    </nav>
    <main>
        <section id="balance">
            <h2>Laporan Balance</h2>
            <form>
                <label for="balance-amount">Balance Hari Ini:</label>
                <input type="number" id="balance-amount" name="balance" required>
                <button type="submit">Kirim</button>
            </form>
            <table>
                <thead>
                    <tr>
                        <th>Tanggal</th>
                        <th>Balance</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>2024-12-26</td>
                        <td>10,000,000</td>
                    </tr>
                </tbody>
            </table>
        </section>
        
        <section id="profit">
            <h2>Profit Harian</h2>
            <form>
                <label for="profit-amount">Profit Hari Ini:</label>
                <input type="number" id="profit-amount" name="profit" required>
                <button type="submit">Kirim</button>
            </form>
            <table>
                <thead>
                    <tr>
                        <th>Tanggal</th>
                        <th>Profit</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>2024-12-26</td>
                        <td>500,000</td>
                    </tr>
                </tbody>
            </table>
        </section>
        
        <section id="transaction">
            <h2>Deposit & Withdrawal</h2>
            <form>
                <label for="deposit-amount">Deposit:</label>
                <input type="number" id="deposit-amount" name="deposit">
                
                <label for="withdrawal-amount">Withdrawal:</label>
                <input type="number" id="withdrawal-amount" name="withdrawal">
                
                <button type="submit">Kirim</button>
            </form>
            <table>
                <thead>
                    <tr>
                        <th>Tanggal</th>
                        <th>Deposit</th>
                        <th>Withdrawal</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>2024-12-26</td>
                        <td>2,000,000</td>
                        <td>1,000,000</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Laporan Harian</p>
    </footer>
</body>
</html>
