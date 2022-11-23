<script>
  let AED = 3.6725;
  let AFN = 88.422797;
  let ALL = 114.144906;
  let AMD = 394.899048;
  let ANG = 1.79;
  let AOA = 509.323585;
  let ARS = 162.804137;
  let AUD = 1.505582;
  let AWG = 1.79;
  let AZN = 1.696648;
  let BAM = 1.902093;
  let BBD = 2;
  let BDT = 101.523661;
  let BGN = 1.902302;
  let BHD = 0.376;
  let BIF = 2040.773175;
  let BMD = 1;
  let BND = 1.378725;
  let BOB = 6.888097;
  let BRL = 5.325257;
  let BSD = 1;
  let BTN = 81.574644;
  let BWP = 13.04769;
  let BYN = 2.483259;
  let BZD = 2;
  let CAD = 1.338448;
  let CDF = 2095.256636;
  let CHF = 0.952508;
  let CLP = 941.5777;
  let CNY = 7.135352;
  let COP = 4933.816225;
  let CRC = 611.654692;
  let CUP = 24;
  let CVE = 107.235434;
  let CZK = 23.702163;
  let DJF = 177.721;
  let DKK = 7.255404;
  let DOP = 54.438814;
  let DZD = 138.940879;
  let EGP = 24.511541;
  let ERN = 15;
  let ETB = 53.172925;
  let EUR = 0.97254;
  let FJD = 2.227661;
  let FKP = 0.842369;
  let FOK = 7.255404;
  let GBP = 0.842376;
  let GEL = 2.717221;
  let GGP = 0.842369;
  let GHS = 15.09631;
  let GIP = 0.842369;
  let GMD = 63.416055;
  let GNF = 8616.838034;
  let GTQ = 7.776889;
  let GYD = 209.406508;
  let HKD = 7.815707;
  let HNL = 24.59764;
  let HRK = 7.327487;
  let HTG = 138.438101;
  let HUF = 395.756966;
  let IDR = 15659.018727;
  let ILS = 3.475209;
  let IMP = 0.842369;
  let INR = 81.576175;
  let IQD = 1460.764519;
  let IRR = 42001.449295;
  let ISK = 142.243427;
  let JEP = 0.842369;
  let JMD = 154.040895;
  let JOD = 0.709;
  let JPY = 141.196332;
  let KES = 122.603359;
  let KGS = 84.372899;
  let KHR = 4146.210404;
  let KID = 1.505634;
  let KMF = 478.45078;
  let KRW = 1352.72794;
  let KWD = 0.29963;
  let KYD = 0.833333;
  let KZT = 463.377416;
  let LAK = 17205.095366;
  let LBP = 1507.5;
  let LKR = 361.2083;
  let LRD = 153.656844;
  let LSL = 17.264846;
  let LYD = 4.90412;
  let MAD = 10.754827;
  let MDL = 19.213427;
  let MGA = 4307.505806;
  let MKD = 60.199021;
  let MMK = 2673.655859;
  let MNT = 3410.289373;
  let MOP = 8.050159;
  let MRU = 37.911193;
  let MUR = 43.446786;
  let MVR = 15.402413;
  let MWK = 1036.229211;
  let MXN = 19.473323;
  let MYR = 4.566528;
  let MZN = 64.513597;
  let NAD = 17.264846;
  let NGN = 442.660667;
  let NIO = 35.834284;
  let NOK = 10.142928;
  let NPR = 130.519431;
  let NZD = 1.626921;
  let OMR = 0.384497;
  let PAB = 1;
  let PEN = 3.845422;
  let PGK = 3.51281;
  let PHP = 57.26368;
  let PKR = 223.781184;
  let PLN = 4.571612;
  let PYG = 7152.870781;
  let QAR = 3.64;
  let RON = 4.793012;
  let RSD = 114.131347;
  let RUB = 60.49989;
  let RWF = 1052.499564;
  let SAR = 3.75;
  let SBD = 8.339362;
  let SCR = 13.350202;
  let SDG = 565.127364;
  let SEK = 10.655097;
  let SGD = 1.37872;
  let SHP = 0.842369;
  let SLE = 18.520193;
  let SLL = 18520.193327;
  let SOS = 569.026229;
  let SRD = 30.757651;
  let SSP = 629.960594;
  let STN = 23.826855;
  let SYP = 2506.930654;
  let SZL = 17.264846;
  let THB = 36.070764;
  let TJS = 10.128159;
  let TMT = 3.499989;
  let TND = 2.907382;
  let TOP = 2.37405;
  let TRY = 18.612083;
  let TTD = 6.765874;
  let TVD = 1.505634;
  let TWD = 31.04253;
  let TZS = 2331.608472;
  let UAH = 36.740758;
  let UGX = 3746.689005;
  let USD = 1;
  let UYU = 39.919384;
  let UZS = 11236.768716;
  let VES = 9.9887;
  let VND = 24793.643452;
  let VUV = 121.202142;
  let WST = 2.743628;
  let XAF = 637.934373;
  let XCD = 2.7;
  let XDR = 0.765854;
  let XOF = 637.934373;
  let XPF = 116.053315;
  let YER = 249.70527;
  let ZAR = 17.264861;
  let ZMW = 16.745591;
  let ZWL = 643.438735;

  fetch("https://open.er-api.com/v6/latest/USD")
    .then((response) => response.json())
    .then(
      (data) => (
        console.log(data),
        console.log(data.rates.EUR),
        (EUR = data.rates.EUR),
        (AED = data.rates.AED),
        (AFN = data.rates.AFN),
        (ALL = data.rates.ALL),
        (AMD = data.rates.AMD),
        (ANG = data.rates.ANG),
        (AOA = data.rates.AOA),
        (ARS = data.rates.ARS),
        (AUD = data.rates.AUD),
        (AWG = data.rates.AWG),
        (AZN = data.rates.AZN),
        (BAM = data.rates.BAM),
        (BBD = data.rates.BBD),
        (BDT = data.rates.BDT),
        (BGN = data.rates.BGN),
        (BHD = data.rates.BHD),
        (BIF = data.rates.BIF),
        (BMD = data.rates.BMD),
        (BND = data.rates.BND),
        (BOB = data.rates.BOB),
        (BRL = data.rates.BRL),
        (BSD = data.rates.BSD),
        (BTN = data.rates.BTN),
        (BWP = data.rates.BWP),
        (BYN = data.rates.BYN),
        (BZD = data.rates.BZD),
        (CAD = data.rates.CAD),
        (CDF = data.rates.CDF),
        (CHF = data.rates.CHF),
        (CLP = data.rates.CLP),
        (CNY = data.rates.CNY),
        (COP = data.rates.COP),
        (CRC = data.rates.CRC),
        (CUP = data.rates.CUP),
        (CVE = data.rates.CVE),
        (CZK = data.rates.CZK),
        (DJF = data.rates.DJF),
        (DKK = data.rates.DKK),
        (DOP = data.rates.DOP),
        (DZD = data.rates.DZD),
        (EGP = data.rates.EGP),
        (ERN = data.rates.ERN),
        (ETB = data.rates.ETB),
        (EUR = data.rates.EUR),
        (FJD = data.rates.FJD),
        (FKP = data.rates.FKP),
        (FOK = data.rates.FOK),
        (GBP = data.rates.GBP),
        (GEL = data.rates.GEL),
        (GGP = data.rates.GGP),
        (GHS = data.rates.GHS),
        (GIP = data.rates.GIP),
        (GMD = data.rates.GMD),
        (GNF = data.rates.GNF),
        (GTQ = data.rates.GTQ),
        (GYD = data.rates.GYD),
        (HKD = data.rates.HKD),
        (HNL = data.rates.HNL),
        (HRK = data.rates.HRK),
        (HTG = data.rates.HTG),
        (HUF = data.rates.HUF),
        (IDR = data.rates.IDR),
        (ILS = data.rates.ILS),
        (IMP = data.rates.IMP),
        (INR = data.rates.INR),
        (IQD = data.rates.IQD),
        (IRR = data.rates.IRR),
        (ISK = data.rates.ISK),
        (JEP = data.rates.JEP),
        (JMD = data.rates.JMD),
        (JOD = data.rates.JOD),
        (JPY = data.rates.JPY),
        (KES = data.rates.KES),
        (KGS = data.rates.KGS),
        (KHR = data.rates.KHR),
        (KID = data.rates.KID),
        (KMF = data.rates.KMF),
        (KRW = data.rates.KRW),
        (KWD = data.rates.KWD),
        (KYD = data.rates.KYD),
        (KZT = data.rates.KZT),
        (LAK = data.rates.LAK),
        (LBP = data.rates.LBP),
        (LKR = data.rates.LKR),
        (LRD = data.rates.LRD),
        (LSL = data.rates.LSL),
        (LYD = data.rates.LYD),
        (MAD = data.rates.MAD),
        (MDL = data.rates.MDL),
        (MGA = data.rates.MGA),
        (MKD = data.rates.MKD),
        (MMK = data.rates.MMK),
        (MNT = data.rates.MNT),
        (MOP = data.rates.MOP),
        (MRU = data.rates.MRU),
        (MUR = data.rates.MUR),
        (MVR = data.rates.MVR),
        (MWK = data.rates.MWK),
        (MXN = data.rates.MXN),
        (MYR = data.rates.MYR),
        (MZN = data.rates.MZN),
        (NAD = data.rates.NAD),
        (NGN = data.rates.NGN),
        (NIO = data.rates.NIO),
        (NOK = data.rates.NOK),
        (NPR = data.rates.NPR),
        (NZD = data.rates.NZD),
        (OMR = data.rates.OMR),
        (PAB = data.rates.PAB),
        (PEN = data.rates.PEN),
        (PGK = data.rates.PGK),
        (PHP = data.rates.PHP),
        (PKR = data.rates.PKR),
        (PLN = data.rates.PLN),
        (PYG = data.rates.PYG),
        (QAR = data.rates.QAR),
        (RON = data.rates.RON),
        (RSD = data.rates.RSD),
        (RUB = data.rates.RUB),
        (RWF = data.rates.RWF),
        (SAR = data.rates.SAR),
        (SBD = data.rates.SBD),
        (SCR = data.rates.SCR),
        (SDG = data.rates.SDG),
        (SEK = data.rates.SEK),
        (SGD = data.rates.SGD),
        (SHP = data.rates.SHP),
        (SLE = data.rates.SLE),
        (SLL = data.rates.SLL),
        (SOS = data.rates.SOS),
        (SRD = data.rates.SRD),
        (SSP = data.rates.SSP),
        (STN = data.rates.STN),
        (SYP = data.rates.SYP),
        (SZL = data.rates.SZL),
        (THB = data.rates.THB),
        (TJS = data.rates.TJS),
        (TMT = data.rates.TMT),
        (TND = data.rates.TND),
        (TOP = data.rates.TOP),
        (TRY = data.rates.TRY),
        (TTD = data.rates.TTD),
        (TVD = data.rates.TVD),
        (TWD = data.rates.TWD),
        (TZS = data.rates.TZS),
        (UAH = data.rates.UAH),
        (UGX = data.rates.UGX),
        (USD = data.rates.USD),
        (UYU = data.rates.UYU),
        (UZS = data.rates.UZS),
        (VES = data.rates.VES),
        (VND = data.rates.VND),
        (VUV = data.rates.VUV),
        (WST = data.rates.WST),
        (XAF = data.rates.XAF),
        (XCD = data.rates.XCD),
        (XDR = data.rates.XDR),
        (XOF = data.rates.XOF),
        (XPF = data.rates.XPF),
        (YER = data.rates.YER),
        (ZAR = data.rates.ZAR),
        (ZMW = data.rates.ZMW),
        (ZWL = data.rates.ZWL)
      )
    );

  // logical functions

  function addMoney(addAmount) {
    console.log(addAmount);
    if (addAmount != 0) {
      payment = payment + amount / selCur;
      localStorage.setItem("storeAmount", String(payment));
      var output = payment * selCur;
      rounded = Number(output.toFixed(2));
    }
  }

  function showMore() {
    let show = document.getElementById("show");
    let load = document.getElementById("load");
    show.style.display = "block";
    load.style.display = "block";
    show.classList.add("showCurrency");
    shown = "true";
  }

  function selCusCur(name) {
    selCur = eval(name);
    var newOutput = payment * selCur;
    rounded = Number(newOutput.toFixed(2));
  }

  // setup

  let curName;
  let shown = "false";
  let amount;
  let money = Number(localStorage.getItem("storeAmount")) / EUR || Number(0);
  let payment = money;
  amount = amount;

  let currency = [
    { name: "💶 EUR" },
    { name: "💵 USD" },
    { name: "💴 JPY" },
    { name: "💷 GBP" },
    { name: "♾️ CUS" },
  ];
  let selectCur = "€";
  let selected;

  // reactive components

  $: {
    if (selected == "💶 EUR") {
      selectCur = "€";
      console.log(String(rounded) + "€");
      selCusCur(EUR);
    }
    if (selected == "💵 USD") {
      selectCur = "$";
      console.log(String(rounded) + "$");
      selCusCur(USD);
    }
    if (selected == "💴 JPY") {
      selectCur = "¥";
      console.log(String(rounded) + "¥");
      selCusCur(JPY);
    }
    if (selected == "💷 GBP") {
      selectCur = "£";
      console.log(String(rounded) + "£");
      selCusCur(GBP);
    }
    if (selected == "♾️ CUS") {
      selectCur = curName || '';
      showMore();
    }
  }

  // first showcase

  let selCur = EUR;
  payment = money * selCur;
  let roundedString = payment.toFixed(2);
  let rounded = Number(roundedString);
</script>

<div class="pay">
  <div>
    <h1>{rounded}{selectCur}</h1>
    <p>/month</p>
  </div>
</div>
<div class="userInput">
  <div class="amount">
    <input
      class="selAmount"
      type="number"
      bind:value={amount}
      placeholder="Enter Amount"
    />
    <input
      class="selCurrency"
      id="show"
      type="text"
      bind:value={curName}
      placeholder="Other currency zB CHF"
    />
    <select bind:value={selected}>
      {#each currency as currency}
        <option>{currency.name}</option>
      {/each}
    </select>
  </div>
  <div class="buttons">
    <button on:click={() => addMoney(amount)}>
      Add {amount||'0'}{selectCur} a month to calculator.
    </button>
    <button
      id="load"
      on:click={() => {
        selCusCur(curName.toUpperCase());
        console.log(String(rounded) + curName);
      }}
      >Load Custum
    </button>
    <button
      on:click={() => {
        localStorage.removeItem("storeAmount");
        location.reload();
      }}
      >Clear
    </button>
  </div>
</div>
<!--
<div class="table-wrapper">
  <div>
    <table class="fl-table">
      <thead>
        <tr>
          <th>Subscriptioname:</th>
          <th>Paymentamount:</th>
          <th>Created on</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Content 8</td>
          <td>Content 8</td>
          <td>Content 8</td>
        </tr>
        <tr>
          <td>Content 9</td>
          <td>Content 9</td>
          <td>Content 9</td>
        </tr>
        <tr>
          <td>Content 10</td>
          <td>Content 10</td>
          <td>Content 10</td>
        </tr>
      </tbody><tbody />
    </table>
  </div>
</div>
-->

<!--lang="sass"-->
<style>
  :root {
    --inputColor: rgb(0, 0, 0);
    --start-color: #7928ca;
    --end-color: #ff0080;
  }

  h1 {
    width: fit-content;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-image: linear-gradient(
      90deg,
      var(--start-color),
      var(--end-color)
    );
  }

  .selAmount,
  .selCurrency {
    width: 100%;
    max-width: 800px;
    height: 2rem;
    border-style: solid;
    border-color: var(--inputColor);
    border-width: 0.25rem;
    color: rgb(255, 255, 255);
    padding: 1rem;
    min-height: 5vh;
    max-height: 25vh;
    font-size: larger;
    border-radius: 1rem 0 0 1rem;
    background-color: var(--inputColor);
    border-right: none;
  }

  .selCurrency {
    border-radius: 0;
    width: 0;
    transition: all 0.5s;
    display: none;
  }

  #load {
    display: none;
  }

  .buttons {
    display: flex;
    gap: 1rem;
  }

  button {
    width: inherit;
    margin-top: 1rem;
    padding: 1rem;
    padding-left: 1.5rem;
    padding-right: 1.5rem;
    border-style: none;
    background-color: rgb(42, 42, 42);
    color: rgb(255, 255, 255);
    border-radius: 100vw;
    transition: ease 0.3s;
    box-shadow: rgba(255, 255, 255, 0.15) 0px 48px 100px 0px;
  }

  button:hover {
    cursor: pointer;
    color: #000;
    background-color: rgb(255, 255, 255);
    box-shadow: rgba(255, 255, 255, 0.6) 0px 5px,
      rgba(255, 255, 255, 0.4) 0px 10px, rgba(255, 255, 255, 0.3) 0px 15px,
      rgba(255, 255, 255, 0.2) 0px 20px, rgba(255, 255, 255, 0.1) 0px 25px,
      rgb(129 129 129 / 25%) 0px 30px 60px -12px inset;
  }

  .pay {
    display: flex;
  }

  .pay div {
    margin: auto;
    display: flex;
    align-content: center;
    align-items: flex-end;
  }

  .pay h1,
  .pay p {
    margin-block-start: 0;
    margin-block-end: 0;
  }

  .userInput {
    display: flex;
    flex-direction: column;
    align-items: center;
    align-content: center;
  }

  .amount {
    display: flex;
    outline-width: 2px;
    outline-style: solid;
    outline-color: #888;
    border-radius: 1rem;
  }

  select {
    height: 2rem;
    border-style: solid;
    border-color: var(--inputColor);
    border-width: 0.25rem;
    min-height: 5vh;
    max-height: 25vh;
    font-size: larger;
    border-radius: 0 1rem 1rem 0;
    background-color: var(--inputColor);
    color: #fff;
  }

  .pay h1 {
    font-size: 8rem;
  }

  .pay p {
    font-size: 2rem;
    margin-bottom: 2rem;
  }

  @media only screen and (max-width: 500px) {
    .pay h1 {
      font-size: 5rem;
    }

    .pay p {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
  }

  /* Table Styles */

  .table-wrapper {
    margin-top: 3rem;
  }

  .table-wrapper div {
    outline-style: solid;
    outline-width: 2px;
    outline-color: #333;
    border-radius: 1.15rem;
  }

  .fl-table {
    border-radius: 1rem;
    font-size: 12px;
    font-weight: normal;
    border: none;
    border-collapse: collapse;
    width: 100%;
    max-width: 100%;
    white-space: nowrap;
    background-color: #161616;
  }

  .fl-table td,
  .fl-table th {
    text-align: center;
    padding: 8px;
    width: 33%;
  }

  .fl-table td {
    font-size: 12px;
  }

  .fl-table thead th:nth-child(1),
  .fl-table thead th:nth-child(2),
  .fl-table thead th:nth-child(3) {
    color: #ffffff;
    background: #7928ca;
    background-image: linear-gradient(90deg, #5eead4, #93c5fd);
  }

  .fl-table thead th:nth-child(1) {
    border-radius: 1rem 0 0 0;
  }

  .fl-table thead th:nth-child(3) {
    border-radius: 0 1rem 0 0;
  }

  .fl-table tr:nth-child(even) {
    background: #1d1d1d;
  }

  /* Responsive */

  @media (max-width: 767px) {
    .fl-table {
      display: block;
      width: 100%;
    }
    .table-wrapper:before {
      content: "Scroll horizontally >";
      display: block;
      text-align: right;
      font-size: 11px;
      color: white;
      padding: 0 0 10px;
    }
    .fl-table thead,
    .fl-table tbody,
    .fl-table thead th {
      display: block;
    }
    .fl-table thead th:last-child {
      border-bottom: none;
    }
    .fl-table thead {
      float: left;
    }
    .fl-table tbody {
      width: auto;
      position: relative;
      overflow-x: auto;
    }
    .fl-table td,
    .fl-table th {
      padding: 20px 0.625em 0.625em 0.625em;
      height: 60px;
      vertical-align: middle;
      box-sizing: border-box;
      overflow-x: hidden;
      overflow-y: auto;
      width: 120px;
      font-size: 13px;
      text-overflow: ellipsis;
    }
    .fl-table thead th {
      text-align: left;
      border-bottom: 1px solid #f7f7f9;
    }
    .fl-table tbody tr {
      display: table-cell;
    }
    .fl-table tbody tr:nth-child(odd) {
      background: none;
    }
    .fl-table tr:nth-child(even) {
      background: transparent;
    }
    .fl-table tr td:nth-child(odd) {
      background: #f8f8f8;
      border-right: 1px solid #e6e4e4;
    }
    .fl-table tr td:nth-child(even) {
      border-right: 1px solid #e6e4e4;
    }
    .fl-table tbody td {
      display: block;
      text-align: center;
    }
  }
</style>
