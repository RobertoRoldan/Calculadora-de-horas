const CACHE_NAME = 'timecalc-v1';
const ASSETS = [
  './',
  './index.html',
  'https://cdn-icons-png.flaticon.com/512/2082/2082582.png'
];

// Instalar y cachear recursos
self.addEventListener('install', (e) => {
  e.waitUntil(
    caches.open(CACHE_NAME).then((cache) => cache.addAll(ASSETS))
  );
});

// Estrategia: Primero Cache, luego Red
self.addEventListener('fetch', (e) => {
  e.respondWith(
    caches.match(e.request).then((res) => res || fetch(e.request))
  );
});