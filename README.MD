<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>LUMÁN · Catálogo Perfumes Sólidos — Ampliado</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#fbf8f4; --card:#fff; --text:#222; --muted:#7a7a7a;
  --honey:#bfa06a; --honey-dark:#9b7f4f; --leaf:#2f6b4a;
  --radius:12px; --shadow:0 10px 30px rgba(20,20,20,0.06);
}
*{box-sizing:border-box}
body{margin:0;font-family:Inter,system-ui,Arial;background:linear-gradient(180deg,#fbf8f4,#f6f3ef);color:var(--text);padding:28px}
header{max-width:1200px;margin:0 auto 24px;display:flex;justify-content:space-between;align-items:center;gap:20px}
.brand{display:flex;gap:16px;align-items:center}
.logo{width:72px;height:72px;border-radius:14px;background:linear-gradient(135deg,rgba(191,160,106,0.12),rgba(191,160,106,0.04));display:flex;align-items:center;justify-content:center;box-shadow:var(--shadow);border:1px solid rgba(0,0,0,0.03)}
.brand h1{margin:0;font-family:'Playfair Display',serif;font-size:26px}
.slogan{color:var(--honey);font-family:'Playfair Display',serif;font-weight:700;text-align:right}
.slogan small{display:block;color:var(--muted);font-family:Inter;font-weight:400;font-size:12px;margin-top:6px}

.wrap{max-width:1200px;margin:0 auto;display:grid;grid-template-columns:1fr 360px;gap:28px}
@media(max-width:1100px){.wrap{grid-template-columns:1fr}}

.catalog{display:grid;gap:22px}
.section{background:var(--card);border-radius:var(--radius);padding:18px;box-shadow:var(--shadow);border:1px solid rgba(0,0,0,0.03)}
.section h2{margin:0 0 8px 0;font-family:'Playfair Display',serif;color:var(--leaf)}
.section p.lead{margin:0 0 14px 0;color:var(--muted);font-size:13px}

.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px}
.card{display:flex;gap:12px;padding:12px;border-radius:12px;background:linear-gradient(180deg,#fff,#fbfaf9);border:1px solid rgba(0,0,0,0.04);align-items:flex-start}
.visual{width:72px;height:72px;border-radius:10px;background:linear-gradient(135deg,#f7f3ee,#efe9e0);display:flex;align-items:center;justify-content:center;flex-shrink:0;overflow:hidden;border:1px solid rgba(0,0,0,0.02)}
.meta h3{margin:0;font-family:'Playfair Display',serif;font-size:15px}
.meta .family{font-size:12px;color:var(--muted);margin-top:6px;font-style:italic}
.meta p.desc{margin:8px 0 0 0;font-size:13px;color:#333;line-height:1.35}
.row{display:flex;gap:8px;align-items:center;margin-top:10px}
.btn{padding:7px 10px;border-radius:8px;border:1px solid rgba(0,0,0,0.06);background:transparent;cursor:pointer;font-size:13px}
.btn.primary{background:linear-gradient(180deg,var(--honey),var(--honey-dark));color:#fff;border:0;box-shadow:0 8px 20px rgba(155,127,79,0.12)}
.icon-bee{width:18px;height:18px;display:inline-block;vertical-align:middle;margin-right:6px;opacity:0.95}

.panel{position:sticky;top:28px;background:linear-gradient(180deg,#fff,#fbfaf9);border-radius:12px;padding:18px;border:1px solid rgba(0,0,0,0.04);box-shadow:var(--shadow);height:max-content}
.panel h4{margin:0 0 8px 0;font-family:'Playfair Display',serif}
.panel p{margin:0 0 12px 0;color:var(--muted);font-size:13px}
.selected{list-style:none;padding:0;margin:0;display:grid;gap:8px}
.selected li{display:flex;justify-content:space-between;align-items:center;padding:8px;border-radius:8px;background:linear-gradient(90deg,rgba(191,160,106,0.06),#fff);font-size:13px}
.chip{background:rgba(47,107,74,0.08);color:var(--leaf);padding:6px 8px;border-radius:8px;font-size:12px}
.copy{margin-top:12px;padding:10px;border-radius:10px;background:var(--honey);color:#fff;border:0;width:100%;cursor:pointer;font-weight:600}
.clear{margin-top:8px;background:transparent;border:0;color:var(--muted);cursor:pointer;font-size:13px}
.divider{height:1px;background:linear-gradient(90deg,transparent,#eee,transparent);margin:14px 0;border-radius:2px}
.muted{color:var(--muted);font-size:12px}

/* Print A4 */
@media print{
  body{padding:0;background:#fff}
  header, .panel .copy, .panel .clear{display:none}
  .wrap{grid-template-columns:1fr}
  .section{page-break-inside:avoid}
  @page{size:A4;margin:20mm}
}
</style>
</head>
<body>

<header>
  <div class="brand">
    <div class="logo" aria-hidden="true">
      <svg viewBox="0 0 64 64" width="48" height="48" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <defs><linearGradient id="g" x1="0" x2="1"><stop offset="0" stop-color="#f6e7c9"/><stop offset="1" stop-color="#f0d9a6"/></linearGradient></defs>
        <rect width="64" height="64" rx="12" fill="url(#g)"/>
        <g transform="translate(8,8)" fill="#2f6b4a">
          <path d="M24 4c-4 0-8 3-8 7s4 7 8 7 8-3 8-7-4-7-8-7z"/>
          <path d="M8 28c0-6 8-10 16-10s16 4 16 10v6H8v-6z" fill="#9b7f4f"/>
        </g>
      </svg>
    </div>
    <div>
      <h1>LUMÁN · Perfumes Sólidos</h1>
      <p class="muted">Edición Premium · Colección botánica</p>
    </div>
  </div>

  <div>
    <div class="slogan">Se desliza, se funde, se queda
      <small>Así se aplica lo invisible</small>
    </div>
  </div>
</header>

<div class="wrap">
  <main class="catalog">

    <!-- HOMBRES -->
    <section class="section" id="hombres">
      <h2>Perfumería Masculina</h2>
      <p class="lead">Aromas cálidos, amaderados y acuáticos adaptados al formato sólido.</p>
      <div class="grid">

        <article class="card" data-name="AYLTAFA · Cuero Solar" data-section="Hombres">
          <div class="visual"><img src="" alt="AYLTAFA" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>AYLTAFA · Cuero Solar <span class="icon-bee" title="LUMÁN"></span></h3>
            <div class="family">Cuero · Ámbar</div>
            <p class="desc">Inspirado en 1 Million Elixir. Evoca piel cálida, madera dorada y presencia magnética; la cera se funde con la piel y deja una estela sofisticada.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="NERA · Agua de Montaña" data-section="Hombres">
          <div class="visual"><img src="" alt="NERA" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>NERA · Agua de Montaña</h3>
            <div class="family">Acuática · Aromática</div>
            <p class="desc">Inspirado en Silver Mountain Water. Frescor mineral, brisa de altura y pureza persistente; ideal para pieles que buscan ligereza y duración.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="VETRA · Cedro Verde" data-section="Hombres">
          <div class="visual"><img src="" alt="VETRA" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>VETRA · Cedro Verde</h3>
            <div class="family">Amaderada · Especiada</div>
            <p class="desc">Inspirado en Terre d’Hermès. Tierra húmeda, corteza viva y especias que respiran; una interpretación sólida con notas de raíz y resina.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="MILLION · Oro Térmico" data-section="Hombres">
          <div class="visual"><img src="" alt="MILLION" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>MILLION · Oro Térmico</h3>
            <div class="family">Amaderada · Especiada</div>
            <p class="desc">Interpretación sólida de un clásico dorado: notas cálidas, especias dulces y un fondo amaderado que permanece.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="INVICTUS · Brisa Marina" data-section="Hombres">
          <div class="visual"><img src="" alt="INVICTUS" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>INVICTUS · Brisa Marina</h3>
            <div class="family">Amaderada · Acuática</div>
            <p class="desc">Fondo amaderado con frescor marino; la versión sólida mantiene la sensación de energía y duración.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="SAUVAGE · Noche Silvestre" data-section="Hombres">
          <div class="visual"><img src="" alt="SAUVAGE" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>SAUVAGE · Noche Silvestre</h3>
            <div class="family">Aromática · Fougere</div>
            <p class="desc">Aromática intensa con notas de bergamota y especias; la textura sólida ofrece control y una estela refinada.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="ARMANI CODE · Sombra Cálida" data-section="Hombres">
          <div class="visual"><img src="" alt="ARMANI CODE" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>ARMANI CODE · Sombra Cálida</h3>
            <div class="family">Ámbar · Especiada</div>
            <p class="desc">Elegancia nocturna en formato sólido: notas cálidas y especiadas con fondo ambarino.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="FAHRENHEIT · Cuero Tostado" data-section="Hombres">
          <div class="visual"><img src="" alt="FAHRENHEIT" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>FAHRENHEIT · Cuero Tostado</h3>
            <div class="family">Amaderado · Cuero</div>
            <p class="desc">Cuero y notas cálidas en una interpretación sólida que resalta la textura y la permanencia.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

      </div>
    </section>

    <!-- MUJERES -->
    <section class="section" id="mujeres">
      <h2>Perfumería Femenina</h2>
      <p class="lead">Composiciones florales, gourmand y ambarinas con un toque botánico.</p>
      <div class="grid">

        <article class="card" data-name="FIRA · Flor de Ámbar" data-section="Mujeres">
          <div class="visual"><img src="" alt="FIRA" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>FIRA · Flor de Ámbar</h3>
            <div class="family">Floral · Ámbar</div>
            <p class="desc">Flor nocturna que brilla en la piel; la versión sólida aporta una estela íntima y cálida.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="ALMA · Vainilla de Medianoche" data-section="Mujeres">
          <div class="visual"><img src="" alt="ALMA" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>ALMA · Vainilla de Medianoche</h3>
            <div class="family">Ámbar · Vainilla</div>
            <p class="desc">Dulzura profunda y envolvente; perfecta para quienes buscan un aroma gourmand y persistente.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="LUMI · Rosa Intensa" data-section="Mujeres">
          <div class="visual"><img src="" alt="LUMI" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>LUMI · Rosa Intensa</h3>
            <div class="family">Floral · Chipre</div>
            <p class="desc">Rosa cristalina con fondo almizclado; elegante y persistente en formato sólido.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="LADY MILLION · Oro Floral" data-section="Mujeres">
          <div class="visual"><img src="" alt="LADY MILLION" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>LADY MILLION · Oro Floral</h3>
            <div class="family">Chipre · Floral</div>
            <p class="desc">Versión sólida de un clásico: brillo floral con fondo ambarino y textura aterciopelada.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="GOOD GIRL · Noche de Jazmín" data-section="Mujeres">
          <div class="visual"><img src="" alt="GOOD GIRL" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>GOOD GIRL · Noche de Jazmín</h3>
            <div class="family">Floral · Amaderada</div>
            <p class="desc">Jazmín y notas orientales en una interpretación sólida, sofisticada y femenina.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="BACCARAT · Rouge Susurro" data-section="Mujeres">
          <div class="visual"><img src="" alt="BACCARAT" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>BACCARAT · Rouge Susurro</h3>
            <div class="family">Ámbar · Floral</div>
            <p class="desc">Interpretación sólida de un gourmand floral de lujo; intensa y persistente.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

      </div>
    </section>

    <!-- UNISEX -->
    <section class="section" id="unisex">
      <h2>Unisex</h2>
      <p class="lead">Aromas versátiles y atemporales para cualquier piel y ocasión.</p>
      <div class="grid">

        <article class="card" data-name="LUZIA · Mandarina Tonka" data-section="Unisex">
          <div class="visual"><img src="" alt="LUZIA" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>LUZIA · Mandarina Tonka</h3>
            <div class="family">Cítrica · Amaderada</div>
            <p class="desc">Explosión cítrica con fondo dulce; la textura sólida ofrece control y duración.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="SANTAL · Madera Blanca" data-section="Unisex">
          <div class="visual"><img src="" alt="SANTAL" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>SANTAL · Madera Blanca</h3>
            <div class="family">Amaderada · Aromática</div>
            <p class="desc">Madera seca y aire limpio; una firma sutil y duradera en formato sólido.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="OUDIA · Ámbar Nocturno" data-section="Unisex">
          <div class="visual"><img src="" alt="OUDIA" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>OUDIA · Ámbar Nocturno</h3>
            <div class="family">Ámbar · Amaderada</div>
            <p class="desc">Profundidad resinosa y misterio; una interpretación sólida con carácter oriental.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="AVENTUS · Bruma de Higo" data-section="Unisex">
          <div class="visual"><img src="" alt="AVENTUS" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>AVENTUS · Bruma de Higo</h3>
            <div class="family">Cítrica · Amaderada</div>
            <p class="desc">Fresco y afrutado con fondo amaderado; la versión sólida mantiene la sofisticación del original.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="BERGAMOTE · Verde Urbano" data-section="Unisex">
          <div class="visual"><img src="" alt="BERGAMOTE" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>BERGAMOTE · Verde Urbano</h3>
            <div class="family">Amaderada · Aromática</div>
            <p class="desc">Cítrica fresca con fondo verde; ideal para uso diario y climas cálidos.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

        <article class="card" data-name="KIRKE · Noche de Almizcle" data-section="Unisex">
          <div class="visual"><img src="" alt="KIRKE" style="width:72px;height:72px;object-fit:cover"></div>
          <div class="meta">
            <h3>KIRKE · Noche de Almizcle</h3>
            <div class="family">Chipre · Frutal</div>
            <p class="desc">Frutal y almizclado; una opción unisex con carácter y elegancia.</p>
            <div class="row"><button class="btn add">Seleccionar</button><button class="btn primary add">Elegir</button></div>
          </div>
        </article>

      </div>
    </section>

  </main>

  <!-- PANEL LATERAL -->
  <aside class="panel" aria-labelledby="panelTitle">
    <h4 id="panelTitle">Selecciones de la gerente</h4>
    <p>Haz clic en <strong>Seleccionar</strong> para añadir; <strong>Elegir</strong> marca como preferida. Copia la lista para pedidos o fichas.</p>

    <ul class="selected" id="selectedList" aria-live="polite"></ul>

    <button class="copy" id="copyBtn">Copiar selección</button>
    <button class="clear" id="clearBtn">Limpiar selecciones</button>

    <div class="divider"></div>
    <div class="muted">Detalles: envase metálico reciclable 14 g; formulación con cera botánica y concentrado aromático. Imprime en A4 para fichas profesionales.</div>
  </aside>
</div>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const selected = JSON.parse(sessionStorage.getItem('luman_selected') || '[]');
  const listEl = document.getElementById('selectedList');
  const copyBtn = document.getElementById('copyBtn');
  const clearBtn = document.getElementById('clearBtn');

  function render(){
    listEl.innerHTML = '';
    selected.forEach((s, idx) => {
      const li = document.createElement('li');
      li.innerHTML = `
        <div style="display:flex;gap:8px;align-items:center">
          <span class="chip">${s.section}</span>
          <strong>${s.name}</strong>
        </div>
        <div style="display:flex;gap:8px;align-items:center">
          ${s.pref ? '<span style="color:var(--honey);font-weight:600">Preferida</span>' : ''}
          <button data-idx="${idx}" aria-label="Eliminar" style="border:0;background:transparent;cursor:pointer;color:#8a8a8a">✕</button>
        </div>`;
      listEl.appendChild(li);
    });
    listEl.querySelectorAll('button[data-idx]').forEach(btn => {
      btn.addEventListener('click', e => {
        const i = Number(e.currentTarget.dataset.idx);
        selected.splice(i,1);
        sessionStorage.setItem('luman_selected', JSON.stringify(selected));
        render();
      });
    });
  }

  document.body.addEventListener('click', e => {
    const btn = e.target.closest('.add');
    if (!btn) return;
    const card = btn.closest('.card');
    if (!card) return;
    const name = card.dataset.name;
    const section = card.dataset.section || 'General';
    const isPref = btn.classList.contains('primary');

    const exists = selected.find(s => s.name === name);
    if (exists) {
      if (isPref) {
        selected.forEach(s => { if (s.section === section) s.pref = false; });
        exists.pref = true;
      } else {
        return;
      }
    } else {
      if (isPref) {
        selected.forEach(s => { if (s.section === section) s.pref = false; });
        selected.push({name, section, pref:true});
      } else {
        selected.push({name, section, pref:false});
      }
    }
    sessionStorage.setItem('luman_selected', JSON.stringify(selected));
    render();
  });

  copyBtn.addEventListener('click', async () => {
    if (selected.length === 0) { alert('No hay fragancias seleccionadas.'); return; }
    const text = selected.map(s => `${s.section} — ${s.name}${s.pref ? ' (Preferida)' : ''}`).join('\n');
    try {
      await navigator.clipboard.writeText(text);
      copyBtn.textContent = 'Copiado';
      setTimeout(()=> copyBtn.textContent = 'Copiar selección', 1400);
    } catch {
      prompt('Copia manual:', text);
    }
  });

  clearBtn.addEventListener('click', () => {
    if (!confirm('¿Limpiar todas las selecciones?')) return;
    selected.length = 0;
    sessionStorage.removeItem('luman_selected');
    render();
  });

  render();
});
</script>

</body>
</html>
