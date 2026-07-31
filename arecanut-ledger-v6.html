<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ledger</title>
<style>
  :root{
    --bg:#0B1420;
    --panel:#131F2E;
    --panel2:#1A2938;
    --border:#243547;
    --gold:#D4A64A;
    --green:#3ECF7E;
    --red:#F0665F;
    --text:#EAF0F6;
    --muted:#7E93A7;
    --blue:#5DA3E0;
  }
  *{box-sizing:border-box; -webkit-tap-highlight-color:transparent;}
  body{
    margin:0;
    background:var(--bg);
    color:var(--text);
    font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',system-ui,sans-serif;
    padding:16px;
    padding-bottom:60px;
  }

  h1{
    font-size:19px;
    margin:0;
    font-weight:700;
    letter-spacing:0.2px;
  }
  .sub{
    color:var(--muted);
    font-size:12px;
    margin-bottom:18px;
  }

  .tabs{
    display:flex;
    gap:6px;
    margin-bottom:16px;
    background:var(--panel);
    padding:4px;
    border-radius:10px;
    border:1px solid var(--border);
  }
  .tab{
    flex:1;
    text-align:center;
    padding:11px 6px;
    border-radius:8px;
    cursor:pointer;
    font-size:13px;
    font-weight:600;
    color:var(--muted);
    transition:all .15s;
  }
  .tab .tab-sub{
    display:block;
    font-size:10px;
    font-weight:400;
    margin-top:1px;
    opacity:0.75;
  }
  .tab.active{
    background:var(--gold);
    color:#1a1408;
  }

  .summary{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:8px;
    margin-bottom:18px;
  }
  .card{
    background:var(--panel);
    border:1px solid var(--border);
    border-radius:10px;
    padding:12px;
  }
  .card .label{
    font-size:10px;
    color:var(--muted);
    text-transform:uppercase;
    letter-spacing:0.6px;
    margin-bottom:4px;
  }
  .card .value{
    font-size:18px;
    font-weight:700;
    font-variant-numeric:tabular-nums;
  }
  .card.wide{grid-column:1/3;}
  .card.balance .value{color:var(--red);}
  .card.balance.negative .value{color:var(--green);}

  .trader-box{
    background:var(--panel);
    border:1px solid var(--border);
    border-radius:10px;
    padding:12px;
    margin-bottom:14px;
  }
  .trader-display{
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:10px;
  }
  .trader-label{
    font-size:10px;
    color:var(--muted);
    text-transform:uppercase;
    letter-spacing:0.6px;
    margin-bottom:3px;
  }
  .trader-name{
    font-size:15px;
    font-weight:700;
    color:var(--gold);
  }
  .trader-name.placeholder{
    color:var(--muted);
    font-weight:400;
    font-size:13px;
  }
  .trader-edit{
    display:none;
    gap:8px;
    margin-top:8px;
  }
  .trader-edit.open{display:flex;}

  .search-box{
    margin-bottom:14px;
  }
  .search-box input{
    background:var(--panel);
  }

  .add-customer{
    display:flex;
    flex-direction:column;
    gap:8px;
    margin-bottom:18px;
    background:var(--panel);
    border:1px solid var(--border);
    border-radius:10px;
    padding:12px;
  }
  .add-customer-row{
    display:flex;
    gap:8px;
  }
  .add-customer .hint{
    font-size:11px;
    color:var(--muted);
  }

  input, select{
    background:var(--panel2);
    border:1px solid var(--border);
    color:var(--text);
    padding:10px;
    border-radius:8px;
    font-size:14px;
    width:100%;
    font-family:inherit;
  }
  input::placeholder{color:#4E6377;}

  button{
    background:var(--gold);
    color:#1a1408;
    border:none;
    padding:10px 16px;
    border-radius:8px;
    font-weight:600;
    font-size:14px;
    cursor:pointer;
    white-space:nowrap;
    font-family:inherit;
  }
  button.secondary{
    background:var(--panel2);
    color:var(--text);
    border:1px solid var(--border);
  }
  button.danger{
    background:#2A1414;
    color:var(--red);
    border:1px solid #4A2020;
  }
  button.whatsapp{
    background:#1F3A2C;
    color:#4FD07C;
    border:1px solid #2C5240;
  }
  button.contact-btn{
    background:var(--panel2);
    color:var(--gold);
    border:1px solid var(--border);
    flex-shrink:0;
  }
  button.small{
    padding:7px 10px;
    font-size:12px;
  }
  button:disabled{
    opacity:0.4;
    cursor:not-allowed;
  }

  .customer{
    background:var(--panel);
    border:1px solid var(--border);
    border-radius:10px;
    margin-bottom:8px;
    overflow:hidden;
  }
  .customer-row{
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:13px 14px;
    cursor:pointer;
    gap:10px;
  }
  .customer-identity{
    display:flex;
    flex-direction:column;
    min-width:0;
    flex:1;
  }
  .customer-name{
    font-weight:600;
    font-size:14.5px;
    white-space:nowrap;
    overflow:hidden;
    text-overflow:ellipsis;
  }
  .customer-phone{
    font-size:11px;
    color:var(--muted);
    margin-top:1px;
  }
  .customer-balance-block{
    text-align:right;
    flex-shrink:0;
  }
  .customer-balance-block .amt{
    font-weight:700;
    font-size:15px;
    font-variant-numeric:tabular-nums;
  }
  .customer-balance-block .tag{
    font-size:9.5px;
    text-transform:uppercase;
    letter-spacing:0.4px;
    color:var(--muted);
  }
  .amt.owe{color:var(--red);}
  .amt.clear{color:var(--muted);}
  .amt.credit{color:var(--green);}
  .chevron{
    color:var(--muted);
    font-size:11px;
    flex-shrink:0;
    transition:transform .15s;
  }
  .chevron.open{transform:rotate(180deg);}

  .customer-body{
    display:none;
    padding:14px;
    border-top:1px solid var(--border);
    background:var(--bg);
  }
  .customer-body.open{display:block;}

  .numbers-grid{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:6px;
    margin-bottom:12px;
  }
  .num-box{
    background:var(--panel2);
    border-radius:8px;
    padding:8px 6px;
    text-align:center;
  }
  .num-box .lbl{
    font-size:9.5px;
    color:var(--muted);
    text-transform:uppercase;
    letter-spacing:0.4px;
    margin-bottom:3px;
  }
  .num-box .val{
    font-size:13px;
    font-weight:700;
    font-variant-numeric:tabular-nums;
  }

  .action-row{
    display:flex;
    gap:8px;
    margin-bottom:14px;
  }
  .action-row button{flex:1;}

  .section-title{
    font-size:11px;
    text-transform:uppercase;
    letter-spacing:0.5px;
    color:var(--muted);
    margin:14px 0 6px 0;
    font-weight:600;
  }

  .new-entry-box{
    background:var(--panel2);
    border:1px solid var(--border);
    border-radius:10px;
    padding:10px;
    display:none;
  }
  .new-entry-box.open{display:block;}
  .add-entry-toggle{
    width:100%;
    background:var(--panel2);
    color:var(--gold);
    border:1px dashed var(--border);
    margin-bottom:10px;
  }
  .new-entry-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:6px;
    margin-bottom:6px;
  }
  .new-entry-grid .field-label{
    font-size:10px;
    color:var(--muted);
    margin-bottom:3px;
    display:block;
  }
  .new-entry-box .date-row{
    margin-bottom:6px;
  }
  .gst-preview{
    display:flex;
    justify-content:space-between;
    background:var(--bg);
    border:1px solid var(--border);
    border-radius:8px;
    padding:8px 10px;
    font-size:12px;
    color:var(--muted);
    margin-bottom:6px;
  }
  .gst-preview b{
    color:var(--gold);
    font-variant-numeric:tabular-nums;
  }
  .new-entry-box .save-btn{
    width:100%;
  }

  .entry-list{
    display:flex;
    flex-direction:column;
    gap:6px;
    margin-bottom:8px;
  }
  .entry{
    display:flex;
    justify-content:space-between;
    align-items:flex-start;
    background:var(--panel2);
    padding:9px 10px;
    border-radius:8px;
    font-size:13px;
  }
  .entry .meta{color:var(--muted); font-size:11px; margin-top:3px;}
  .entry .amt-line{font-weight:600; font-variant-numeric:tabular-nums; display:flex; align-items:center; flex-wrap:wrap; gap:4px;}
  .entry .del{
    color:var(--red);
    cursor:pointer;
    font-size:15px;
    padding:2px 6px;
    line-height:1;
    flex-shrink:0;
  }

  .empty{
    text-align:center;
    color:var(--muted);
    padding:36px 10px;
    font-size:13px;
  }
  .empty-entries{
    color:var(--muted);
    font-size:12px;
    padding:8px 0;
  }

  .qtag{
    font-size:10px;
    padding:2px 6px;
    border-radius:4px;
    background:#243547;
    color:var(--muted);
  }
  .qtag.paid{color:var(--blue); background:#16283A;}

  .modal-overlay{
    display:none;
    position:fixed;
    inset:0;
    background:rgba(0,0,0,0.6);
    z-index:100;
    align-items:flex-end;
    justify-content:center;
  }
  .modal-overlay.open{display:flex;}
  .modal{
    background:var(--panel);
    border:1px solid var(--border);
    border-radius:16px 16px 0 0;
    padding:20px 16px calc(20px + env(safe-area-inset-bottom));
    width:100%;
    max-width:480px;
  }
  .modal h3{
    margin:0 0 4px 0;
    font-size:16px;
  }
  .modal .modal-sub{
    color:var(--muted);
    font-size:12px;
    margin-bottom:14px;
  }
  .modal textarea{
    width:100%;
    background:var(--panel2);
    border:1px solid var(--border);
    color:var(--text);
    border-radius:8px;
    padding:10px;
    font-size:13px;
    font-family:inherit;
    min-height:150px;
    resize:vertical;
    margin-bottom:12px;
  }
  .modal-actions{
    display:flex;
    gap:8px;
  }
  .modal-actions button{flex:1;}
</style>
</head>
<body>

<div id="customerViewApp" style="display:none;"></div>

<div id="adminApp">
<h1>Arecanut Ledger</h1>
<div class="sub">Track bills, GST and payments per customer</div>

<div class="trader-box">
  <div class="trader-display" id="traderDisplay">
    <div>
      <div class="trader-label">Business / Trader Name</div>
      <div class="trader-name placeholder" id="traderNameText">Tap Edit to set your business name</div>
    </div>
    <button class="secondary small" onclick="editTrader()">Edit</button>
  </div>
  <div class="trader-edit" id="traderEdit">
    <input type="text" id="traderNameInput" placeholder="e.g. SFS Traders">
    <button class="small" onclick="saveTrader()">Save</button>
  </div>
</div>

<div class="tabs">
  <div class="tab active" data-tab="sale" onclick="switchTab('sale')">
    Sale Bills<span class="tab-sub">Customer owes you</span>
  </div>
  <div class="tab" data-tab="purchase" onclick="switchTab('purchase')">
    Purchase Bills<span class="tab-sub">You owe supplier</span>
  </div>
</div>

<div class="summary" id="summary"></div>

<div class="add-customer">
  <div class="add-customer-row">
    <input type="text" id="newCustomerName" placeholder="Customer name">
  </div>
  <div class="add-customer-row">
    <input type="tel" id="newCustomerPhone" placeholder="Phone number (optional)">
    <button class="contact-btn" onclick="pickContact()">From Contacts</button>
  </div>
  <button onclick="addCustomer()">Add Customer</button>
  <div class="hint">Add phone number to send ledger details on WhatsApp later. Contact import needs browser support and permission.</div>
</div>

<div class="search-box">
  <input type="text" id="searchBox" placeholder="Search customer by name or phone" oninput="render()">
</div>

<div id="customerList"></div>
</div>

<div class="modal-overlay" id="waModal">
  <div class="modal">
    <h3>Send on WhatsApp</h3>
    <div class="modal-sub" id="waSub"></div>
    <textarea id="waText" readonly></textarea>
    <div class="modal-actions">
      <button class="secondary" onclick="closeWaModal()">Cancel</button>
      <button class="whatsapp" id="waOpenBtn" onclick="openWhatsApp()">Open WhatsApp</button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="shareModal">
  <div class="modal">
    <h3>Customer View Link</h3>
    <div class="modal-sub">This link shows only this customer's own bill, GST, payment and balance details — not your other customers.</div>
    <textarea id="shareLinkText" readonly></textarea>
    <div class="modal-sub" style="margin-top:-6px; margin-bottom:12px;">Note: this link only works correctly if the app is hosted at a fixed web address (e.g. published on GitHub/Cloudflare Pages) and reopened from there — not every "share" method preserves the link the same way.</div>
    <div class="modal-actions">
      <button class="secondary" onclick="closeShareModal()">Cancel</button>
      <button class="whatsapp" id="shareWaBtn" onclick="shareViaWhatsApp()">Send via WhatsApp</button>
    </div>
  </div>
</div>

<script>
let data = { sale: [], purchase: [] };
let currentTab = 'sale';
let openCustomerId = null;
let loaded = false;
let waPendingPhone = '';
let traderName = '';
let entryFormOpenFor = null;

function uid(){ return Date.now().toString(36) + Math.random().toString(36).slice(2,7); }

async function loadTraderName(){
  try{
    const res = await window.storage.get('arecanut-trader-name');
    if(res && res.value){
      traderName = res.value;
    }
  }catch(e){ /* not set yet */ }
  renderTraderBox();
}

function renderTraderBox(){
  const textEl = document.getElementById('traderNameText');
  if(traderName){
    textEl.textContent = traderName;
    textEl.classList.remove('placeholder');
  } else {
    textEl.textContent = 'Tap Edit to set your business name';
    textEl.classList.add('placeholder');
  }
  document.getElementById('traderEdit').classList.remove('open');
}

function editTrader(){
  document.getElementById('traderEdit').classList.add('open');
  document.getElementById('traderNameInput').value = traderName;
  document.getElementById('traderNameInput').focus();
}

async function saveTrader(){
  const val = document.getElementById('traderNameInput').value.trim();
  traderName = val;
  try{
    await window.storage.set('arecanut-trader-name', traderName);
    await window.storage.set('share-trader-name', traderName, true);
  }catch(e){
    console.error('Could not save trader name', e);
  }
  renderTraderBox();
}

async function loadData(){
  try{
    const res = await window.storage.get('arecanut-ledger-data-v3');
    if(res && res.value){
      data = JSON.parse(res.value);
    }
  }catch(e){
    // try migrating from v2 (separate bills/payments arrays)
    try{
      const old = await window.storage.get('arecanut-ledger-data-v2');
      if(old && old.value){
        const parsed = JSON.parse(old.value);
        const migrate = (arr) => (arr||[]).map(c => {
          const txns = [];
          (c.bills||[]).forEach(b => txns.push({id:b.id, date:b.date, billAmt:b.billAmt||0, gstAmt:b.gstAmt||0, paidAmt:0}));
          (c.payments||[]).forEach(p => txns.push({id:p.id, date:p.date, billAmt:0, gstAmt:0, paidAmt:p.amt||0}));
          txns.sort((a,b)=>a.date.localeCompare(b.date));
          return {id:c.id, name:c.name, phone:c.phone||'', transactions:txns};
        });
        data = { sale: migrate(parsed.sale), purchase: migrate(parsed.purchase) };
        await saveData();
      }
    }catch(e2){
      console.log('Starting fresh ledger');
    }
  }
  loaded = true;
  render();
}

async function saveData(){
  try{
    await window.storage.set('arecanut-ledger-data-v3', JSON.stringify(data));
  }catch(e){
    console.error('Save failed', e);
  }
}

function switchTab(tab){
  currentTab = tab;
  openCustomerId = null;
  document.querySelectorAll('.tab').forEach(t=>t.classList.toggle('active', t.dataset.tab===tab));
  render();
}

async function pickContact(){
  try{
    if('contacts' in navigator && 'ContactsManager' in window){
      const props = ['name','tel'];
      const opts = {multiple:false};
      const contacts = await navigator.contacts.select(props, opts);
      if(contacts && contacts.length){
        const c = contacts[0];
        if(c.name && c.name[0]) document.getElementById('newCustomerName').value = c.name[0];
        if(c.tel && c.tel[0]) document.getElementById('newCustomerPhone').value = c.tel[0];
      }
    } else {
      alert('Contact import is not available in this browser/app. Please type the name and phone number manually.');
    }
  }catch(e){
    alert('Could not open contacts. Please enter details manually.');
  }
}

function addCustomer(){
  const nameInput = document.getElementById('newCustomerName');
  const phoneInput = document.getElementById('newCustomerPhone');
  const name = nameInput.value.trim();
  const phone = phoneInput.value.trim();
  if(!name) return;

  const existing = data[currentTab].find(c => c.name.trim().toLowerCase() === name.toLowerCase());
  if(existing){
    if(phone && !existing.phone) existing.phone = phone;
    nameInput.value = '';
    phoneInput.value = '';
    openCustomerId = existing.id;
    entryFormOpenFor = existing.id;
    saveData();
    syncSharedView(currentTab, existing);
    render();
    const rowEl = document.getElementById('customer-'+existing.id);
    if(rowEl) rowEl.scrollIntoView({behavior:'smooth', block:'center'});
    return;
  }

  const newCustomer = { id: uid(), name, phone, transactions: [] };
  data[currentTab].push(newCustomer);
  nameInput.value = '';
  phoneInput.value = '';
  openCustomerId = newCustomer.id;
  entryFormOpenFor = newCustomer.id;
  saveData();
  syncSharedView(currentTab, newCustomer);
  render();
  const rowEl = document.getElementById('customer-'+newCustomer.id);
  if(rowEl) rowEl.scrollIntoView({behavior:'smooth', block:'center'});
}

function deleteCustomer(id){
  if(!confirm('Delete this customer and all their entries?')) return;
  data[currentTab] = data[currentTab].filter(c=>c.id!==id);
  saveData();
  render();
}

function toggleCustomer(id){
  openCustomerId = openCustomerId === id ? null : id;
  render();
}

function toggleEntryForm(id){
  entryFormOpenFor = entryFormOpenFor === id ? null : id;
  render();
  if(entryFormOpenFor === id){
    const dateEl = document.getElementById('entry-date-'+id);
    if(dateEl) dateEl.scrollIntoView({behavior:'smooth', block:'center'});
  }
}

function updateGstPreview(customerId){
  const billEl = document.getElementById('entry-bill-'+customerId);
  const pctEl = document.getElementById('entry-gstpct-'+customerId);
  const bill = parseFloat(billEl.value) || 0;
  const pct = parseFloat(pctEl.value) || 0;
  const gstAmt = bill * pct / 100;
  const total = bill + gstAmt;
  const amtEl = document.getElementById('gst-preview-amt-'+customerId);
  const totalEl = document.getElementById('gst-preview-total-'+customerId);
  if(amtEl) amtEl.textContent = fmt(gstAmt);
  if(totalEl) totalEl.textContent = fmt(total);
}

function saveEntry(customerId){
  const dateEl = document.getElementById('entry-date-'+customerId);
  const billEl = document.getElementById('entry-bill-'+customerId);
  const pctEl = document.getElementById('entry-gstpct-'+customerId);
  const paidEl = document.getElementById('entry-paid-'+customerId);

  const billAmt = parseFloat(billEl.value) || 0;
  const gstPct = parseFloat(pctEl.value) || 0;
  const gstAmt = Math.round((billAmt * gstPct / 100) * 100) / 100;
  const paidAmt = parseFloat(paidEl.value) || 0;

  if(billAmt<=0 && paidAmt<=0){
    alert('Enter at least a bill amount or a payment amount');
    return;
  }

  const customer = data[currentTab].find(c=>c.id===customerId);
  customer.transactions.push({
    id: uid(),
    date: dateEl.value || new Date().toISOString().slice(0,10),
    billAmt, gstAmt, gstPct, paidAmt
  });
  billEl.value=''; pctEl.value=''; paidEl.value='';
  updateGstPreview(customerId);
  entryFormOpenFor = null;
  saveData();
  syncSharedView(currentTab, customer);
  render();
}

async function syncSharedView(tab, customer){
  try{
    await window.storage.set(`share-${tab}-${customer.id}`, JSON.stringify({
      customerName: customer.name,
      phone: customer.phone,
      transactions: customer.transactions
    }), true);
  }catch(e){
    console.error('Could not sync share link data', e);
  }
}

function deleteEntry(customerId, entryId){
  const customer = data[currentTab].find(c=>c.id===customerId);
  customer.transactions = customer.transactions.filter(t=>t.id!==entryId);
  saveData();
  syncSharedView(currentTab, customer);
  render();
}

function customerTotals(c){
  const totalBill = c.transactions.reduce((s,t)=>s+(t.billAmt||0),0);
  const totalGst = c.transactions.reduce((s,t)=>s+(t.gstAmt||0),0);
  const totalDue = totalBill + totalGst;
  const totalPaid = c.transactions.reduce((s,t)=>s+(t.paidAmt||0),0);
  const balance = totalDue - totalPaid;
  return { totalBill, totalGst, totalDue, totalPaid, balance };
}

function fmt(n){
  return '\u20B9' + (n||0).toLocaleString('en-IN', {maximumFractionDigits:2});
}

function openWaModal(customerId){
  const customer = data[currentTab].find(c=>c.id===customerId);
  const t = customerTotals(customer);
  const direction = currentTab==='sale' ? 'Balance Due' : 'Balance Payable to You';
  let balanceLine = 'Balance: Clear';
  if(t.balance > 0) balanceLine = `${direction}: ${fmt(t.balance)}`;
  else if(t.balance < 0) balanceLine = `Advance Paid: ${fmt(Math.abs(t.balance))}`;

  const header = traderName ? `*${traderName}*` : `*Trading Account*`;

  const lines = [
    header,
    `Customer: ${customer.name}`,
    ``,
    `Bill Amount: ${fmt(t.totalBill)}`,
    `GST Amount: ${fmt(t.totalGst)}`,
    `Total Amount: ${fmt(t.totalDue)}`,
    `Amount Paid: ${fmt(t.totalPaid)}`,
    ``,
    balanceLine
  ];
  const text = lines.join('\n');
  document.getElementById('waText').value = text;
  document.getElementById('waSub').textContent = customer.phone
    ? `To: ${customer.name} (${customer.phone})`
    : `To: ${customer.name} — no phone number saved, add one to open WhatsApp directly.`;
  waPendingPhone = (customer.phone || '').replace(/[^0-9]/g,'');
  document.getElementById('waOpenBtn').disabled = !waPendingPhone;
  document.getElementById('waModal').classList.add('open');
}

function closeWaModal(){
  document.getElementById('waModal').classList.remove('open');
}

function openWhatsApp(){
  const text = encodeURIComponent(document.getElementById('waText').value);
  let phone = waPendingPhone;
  if(phone.length === 10) phone = '91' + phone;
  window.open(`https://wa.me/${phone}?text=${text}`, '_blank');
  closeWaModal();
}

let shareModalPhone = '';

async function openShareModal(customerId){
  const customer = data[currentTab].find(c=>c.id===customerId);
  await syncSharedView(currentTab, customer);
  const url = `${window.location.origin}${window.location.pathname}?view=${customer.id}&tab=${currentTab}`;
  document.getElementById('shareLinkText').value = url;
  shareModalPhone = (customer.phone || '').replace(/[^0-9]/g,'');
  document.getElementById('shareModal').classList.add('open');
}

function closeShareModal(){
  document.getElementById('shareModal').classList.remove('open');
}

function shareViaWhatsApp(){
  const url = document.getElementById('shareLinkText').value;
  const text = encodeURIComponent(`Here is your account details link:\n${url}`);
  let phone = shareModalPhone;
  if(phone.length === 10) phone = '91' + phone;
  const target = phone ? `https://wa.me/${phone}?text=${text}` : `https://wa.me/?text=${text}`;
  window.open(target, '_blank');
  closeShareModal();
}

function render(){
  if(!loaded) return;
  const fullList = data[currentTab];
  const searchEl = document.getElementById('searchBox');
  const q = searchEl ? searchEl.value.trim().toLowerCase() : '';
  const list = q ? fullList.filter(c =>
    c.name.toLowerCase().includes(q) || (c.phone||'').toLowerCase().includes(q)
  ) : fullList;

  let sumBill=0, sumGst=0, sumPaid=0, sumBalancePositive=0, sumBalanceNegative=0;
  fullList.forEach(c=>{
    const t = customerTotals(c);
    sumBill += t.totalBill;
    sumGst += t.totalGst;
    sumPaid += t.totalPaid;
    if(t.balance>0) sumBalancePositive += t.balance;
    else sumBalanceNegative += Math.abs(t.balance);
  });
  const sumTotal = sumBill + sumGst;
  const label = currentTab==='sale' ? 'Balance Receivable' : 'Balance Payable';

  document.getElementById('summary').innerHTML = `
    <div class="card"><div class="label">Total Bill Amount</div><div class="value">${fmt(sumBill)}</div></div>
    <div class="card"><div class="label">Total GST Amount</div><div class="value">${fmt(sumGst)}</div></div>
    <div class="card wide"><div class="label">Total Amount (Bill + GST)</div><div class="value" style="color:var(--gold)">${fmt(sumTotal)}</div></div>
    <div class="card"><div class="label">Total ${currentTab==='sale'?'Received':'Paid'}</div><div class="value" style="color:var(--blue)">${fmt(sumPaid)}</div></div>
    <div class="card balance"><div class="label">${label}</div><div class="value">${fmt(sumBalancePositive)}</div></div>
    ${sumBalanceNegative>0 ? `<div class="card wide balance negative"><div class="label">Advance / Overpaid</div><div class="value">${fmt(sumBalanceNegative)}</div></div>` : ''}
  `;

  if(list.length===0){
    const msg = q ? `No customer matches "${q}".` : 'No customers yet. Add one above to get started.';
    document.getElementById('customerList').innerHTML = `<div class="empty">${msg}</div>`;
    return;
  }

  document.getElementById('customerList').innerHTML = list.map(c=>{
    const t = customerTotals(c);
    const isOpen = openCustomerId === c.id;
    let balClass = 'clear', balTag = 'Clear', balVal = fmt(0);
    if(t.balance > 0){
      balClass='owe';
      balTag = currentTab==='sale' ? 'Receivable' : 'Payable';
      balVal = fmt(t.balance);
    } else if(t.balance < 0){
      balClass='credit';
      balTag = 'Advance';
      balVal = fmt(Math.abs(t.balance));
    }

    const sortedTxns = [...c.transactions].sort((a,b)=>b.date.localeCompare(a.date));
    const txnsHtml = sortedTxns.length ? sortedTxns.map(tx=>{
      const parts = [];
      if(tx.billAmt>0) parts.push(`<span class="qtag">Bill ${fmt(tx.billAmt)}</span>`);
      if(tx.gstAmt>0) parts.push(`<span class="qtag">GST ${fmt(tx.gstAmt)}</span>`);
      if(tx.paidAmt>0) parts.push(`<span class="qtag paid">Paid ${fmt(tx.paidAmt)}</span>`);
      return `
        <div class="entry">
          <div>
            <div class="amt-line">${parts.join('')}</div>
            <div class="meta">${tx.date}</div>
          </div>
          <span class="del" onclick="deleteEntry('${c.id}','${tx.id}')">&times;</span>
        </div>
      `;
    }).join('') : `<div class="empty-entries">No entries yet</div>`;

    return `
      <div class="customer" id="customer-${c.id}">
        <div class="customer-row" onclick="toggleCustomer('${c.id}')">
          <div class="customer-identity">
            <div class="customer-name">${c.name}</div>
            ${c.phone ? `<div class="customer-phone">${c.phone}</div>` : ''}
          </div>
          <div class="customer-balance-block">
            <div class="amt ${balClass}">${balVal}</div>
            <div class="tag">${balTag}</div>
          </div>
          <div class="chevron ${isOpen?'open':''}">&#9660;</div>
        </div>
        <div class="customer-body ${isOpen?'open':''}">
          <div class="numbers-grid">
            <div class="num-box"><div class="lbl">Bill</div><div class="val">${fmt(t.totalBill)}</div></div>
            <div class="num-box"><div class="lbl">GST</div><div class="val">${fmt(t.totalGst)}</div></div>
            <div class="num-box"><div class="lbl">Total</div><div class="val" style="color:var(--gold)">${fmt(t.totalDue)}</div></div>
            <div class="num-box"><div class="lbl">Paid</div><div class="val" style="color:var(--blue)">${fmt(t.totalPaid)}</div></div>
          </div>

          <div class="action-row">
            <button class="whatsapp" onclick="openWaModal('${c.id}')">Send on WhatsApp</button>
            <button class="secondary" onclick="openShareModal('${c.id}')">Share Link</button>
          </div>
          <div class="action-row">
            <button class="danger" onclick="deleteCustomer('${c.id}')">Delete Customer</button>
          </div>

          <div class="section-title">Add Entry</div>
          <button class="add-entry-toggle" onclick="toggleEntryForm('${c.id}')">${entryFormOpenFor===c.id ? 'Hide Entry Form' : '+ Add Entry'}</button>
          <div class="new-entry-box ${entryFormOpenFor===c.id ? 'open' : ''}">
            <div class="date-row">
              <span class="field-label">Date</span>
              <input type="date" id="entry-date-${c.id}">
            </div>
            <div class="new-entry-grid">
              <div>
                <span class="field-label">Bill Amount</span>
                <input type="number" id="entry-bill-${c.id}" placeholder="0" oninput="updateGstPreview('${c.id}')">
              </div>
              <div>
                <span class="field-label">GST %</span>
                <input type="number" id="entry-gstpct-${c.id}" placeholder="0" oninput="updateGstPreview('${c.id}')">
              </div>
            </div>
            <div class="gst-preview" id="gst-preview-${c.id}">
              <span>GST Amount: <b id="gst-preview-amt-${c.id}">₹0</b></span>
              <span>Total: <b id="gst-preview-total-${c.id}">₹0</b></span>
            </div>
            <div class="new-entry-grid" style="grid-template-columns:1fr;">
              <div>
                <span class="field-label">Payment Received/Paid</span>
                <input type="number" id="entry-paid-${c.id}" placeholder="0">
              </div>
            </div>
            <button class="save-btn" onclick="saveEntry('${c.id}')">Save Entry</button>
          </div>

          <div class="section-title">History</div>
          <div class="entry-list">${txnsHtml}</div>
        </div>
      </div>
    `;
  }).join('');
}

async function renderCustomerViewPage(tab, id){
  const container = document.getElementById('customerViewApp');
  document.getElementById('adminApp').style.display = 'none';
  container.style.display = 'block';
  container.innerHTML = `<div class="empty">Loading...</div>`;

  let trader = '';
  let cdata = null;
  try{
    const traderRes = await window.storage.get('share-trader-name', true);
    trader = traderRes ? traderRes.value : '';
  }catch(e){ /* no trader name set */ }

  try{
    const res = await window.storage.get(`share-${tab}-${id}`, true);
    if(res && res.value) cdata = JSON.parse(res.value);
  }catch(e){ /* not found */ }

  if(!cdata){
    container.innerHTML = `<div class="empty">This link is not valid, or no details have been added yet. Please check with ${trader || 'the trader'} for an updated link.</div>`;
    return;
  }

  const t = customerTotals(cdata);
  const direction = tab==='sale' ? 'Balance Due' : 'Balance Payable to You';
  let balHtml = `<div class="num-box balance"><div class="lbl">Status</div><div class="val" style="color:var(--muted)">Clear</div></div>`;
  if(t.balance > 0){
    balHtml = `<div class="num-box balance"><div class="lbl">${direction}</div><div class="val" style="color:var(--red)">${fmt(t.balance)}</div></div>`;
  } else if(t.balance < 0){
    balHtml = `<div class="num-box balance"><div class="lbl">Advance Paid</div><div class="val" style="color:var(--green)">${fmt(Math.abs(t.balance))}</div></div>`;
  }

  const sortedTxns = [...cdata.transactions].sort((a,b)=>b.date.localeCompare(a.date));
  const txnsHtml = sortedTxns.length ? sortedTxns.map(tx=>{
    const parts = [];
    if(tx.billAmt>0) parts.push(`<span class="qtag">Bill ${fmt(tx.billAmt)}</span>`);
    if(tx.gstAmt>0) parts.push(`<span class="qtag">GST ${fmt(tx.gstAmt)}${tx.gstPct?` (${tx.gstPct}%)`:''}</span>`);
    if(tx.paidAmt>0) parts.push(`<span class="qtag paid">Paid ${fmt(tx.paidAmt)}</span>`);
    return `<div class="entry"><div><div class="amt-line">${parts.join('')}</div><div class="meta">${tx.date}</div></div></div>`;
  }).join('') : `<div class="empty-entries">No entries yet</div>`;

  container.innerHTML = `
    <div class="trader-box">
      <div class="trader-label">Business</div>
      <div class="trader-name">${trader || 'Trading Account'}</div>
    </div>
    <div class="customer">
      <div class="customer-row" style="cursor:default;">
        <div class="customer-identity">
          <div class="customer-name">${cdata.customerName}</div>
          ${cdata.phone ? `<div class="customer-phone">${cdata.phone}</div>` : ''}
        </div>
      </div>
      <div class="customer-body open">
        <div class="numbers-grid">
          <div class="num-box"><div class="lbl">Bill</div><div class="val">${fmt(t.totalBill)}</div></div>
          <div class="num-box"><div class="lbl">GST</div><div class="val">${fmt(t.totalGst)}</div></div>
          <div class="num-box"><div class="lbl">Total</div><div class="val" style="color:var(--gold)">${fmt(t.totalDue)}</div></div>
          <div class="num-box"><div class="lbl">Paid</div><div class="val" style="color:var(--blue)">${fmt(t.totalPaid)}</div></div>
        </div>
        ${balHtml}
        <div class="section-title" style="margin-top:14px;">History</div>
        <div class="entry-list">${txnsHtml}</div>
      </div>
    </div>
  `;
}

function init(){
  const params = new URLSearchParams(window.location.search);
  const viewId = params.get('view');
  const viewTab = params.get('tab');
  if(viewId && viewTab){
    renderCustomerViewPage(viewTab, viewId);
    return;
  }
  loadTraderName();
  loadData();
}

init();
</script>

</body>
</html>
