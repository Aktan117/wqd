let mode = 'price'; // Алдымен баға енгізіледі

function setMode(m) {
  mode = m;
}

function press(num) {
  if (mode === 'price') {
    document.getElementById('price').value += num;
  } else {
    document.getElementById('discount').value += num;
  }
}

function clearAll() {
  document.getElementById('price').value = '';
  document.getElementById('discount').value = '';
  document.getElementById('result').value = '';
}

// 🔙 ТЕК СОҢҒЫ САНДЫ ӨШІРУ
function backspace() {
  if (mode === 'price') {
    let price = document.getElementById('price').value;
    document.getElementById('price').value = price.slice(0, -1);
  } else {
    let discount = document.getElementById('discount').value;
    document.getElementById('discount').value = discount.slice(0, -1);
  }
}

function calculate() {
  let price = parseFloat(document.getElementById('price').value);
  let discount = parseFloat(document.getElementById('discount').value);

  if (isNaN(price) || isNaN(discount)) {
    document.getElementById('result').value = 'Қате!';
    return;
  }

  let finalPrice = price - (price * discount / 100);
  document.getElementById('result').value = finalPrice.toFixed(2) + ' ₸';
}


const CACHE_NAME = 'my-site-cache-v1';
const urlsToCache = [
  '/',
  '/wqd/',
  '/wqd/index.html',
  '/wqd/style.css',
  '/wqd/script.js',
  '/wqd/icon-192.png',
  '/wqd/icon-512.png'
];

self.addEventListener('install', (event) => {
  event.waitUntil(
    caches.open(CACHE_NAME)
      .then((cache) => cache.addAll(urlsToCache))
  );
});

self.addEventListener('fetch', (event) => {
  event.respondWith(
    caches.match(event.request).then((response) => {
      return response || fetch(event.request);
    })
  );
});
