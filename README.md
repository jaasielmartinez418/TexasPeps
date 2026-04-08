
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TexasPeps | Research Peptides</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #020617;
    color: #e2e8f0;
}

header {
    background: #020617;
    padding: 25px;
    text-align: center;
    border-bottom: 1px solid #1e293b;
}

h1 {
    margin: 0;
    color: #38bdf8;
    letter-spacing: 1px;
}

.tagline {
    color: #94a3b8;
    font-size: 14px;
}

.container {
    max-width: 1100px;
    margin: auto;
    padding: 40px 20px;
}

.section-title {
    margin-bottom: 20px;
    border-left: 4px solid #38bdf8;
    padding-left: 10px;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.product {
    background: #0f172a;
    padding: 20px;
    border-radius: 12px;
    border: 1px solid #1e293b;
    transition: 0.3s;
}

.product:hover {
    border-color: #38bdf8;
}

button {
    margin-top: 10px;
    background: #38bdf8;
    border: none;
    padding: 10px 15px;
    border-radius: 6px;
    cursor: pointer;
    font-weight: bold;
}

button:hover {
    opacity: 0.85;
}

.notice {
    background: #7f1d1d;
    padding: 15px;
    border-radius: 8px;
    margin-bottom: 30px;
    font-size: 14px;
}

footer {
    text-align: center;
    padding: 25px;
    font-size: 12px;
    color: #64748b;
    border-top: 1px solid #1e293b;
}
</style>

</head>
<body>

<header>
    <h1>TexasPeps</h1>
    <div class="tagline">Research Peptides | Laboratory Use Only</div>
</header>

<div class="container">

    <div class="notice">
        ⚠️ All products are strictly for laboratory research purposes only. 
        Not for human consumption or medical use.
    </div>

    <h2 class="section-title">Products</h2>

    <div class="products">

        <div class="product">
            <h3>Retatrutide – 10mg</h3>
            <p>Lyophilized peptide, high purity research compound.</p>
            <p><strong>Availability:</strong> In Stock</p>
            <button onclick="contact()">Request Order</button>
        </div>

        <div class="product">
            <h3>Retatrutide – 30mg</h3>
            <p>Lyophilized peptide, high purity research compound.</p>
            <p><strong>Availability:</strong> In Stock</p>
            <button onclick="contact()">Request Order</button>
        </div>

    </div>

    <h2 class="section-title">About TxPeps</h2>
    <p>
    TxPeps is a supplier of research peptides intended exclusively for laboratory and scientific research use. 
    We are committed to providing high-quality compounds for qualified research environments.
    </p>

    <h2 class="section-title">Contact</h2>
    <p>Email: txpeps@email.com</p>

</div>

<footer>
    DISCLAIMER: Products sold by TxPeps are intended for laboratory research purposes only. 
    They are not intended for human consumption, medical, veterinary, or household use. 
    By purchasing, you acknowledge compliance with all applicable laws and regulations.
</footer>

<script>
function contact() {
    alert("Email txpeps@email.com to place an order.");
}
</script>

</body>
</html>
