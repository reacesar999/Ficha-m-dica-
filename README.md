# Ficha-m-dica-
Ficha médica 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ficha Médica de Emergencia (ICE)</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    @media print {
      .no-print { display: none !important; }
      body { background: white !important; }
    }
  </style>
</head>
<body class="bg-slate-100 text-slate-800 min-h-screen py-6 px-4">
  <main class="max-w-md mx-auto bg-white rounded-3xl shadow-xl overflow-hidden border border-slate-200">
    <!-- Encabezado de Emergencia -->
    <header class="bg-red-600 text-white p-5 flex items-center justify-between">
      <div class="flex items-center space-x-3">
        <i class="fa-solid fa-heart-pulse text-3xl animate-pulse"></i>
        <div>
          <h1 class="font-black text-xl tracking-tight leading-none uppercase">Ficha Médica</h1>
          <p class="text-xs text-red-100 font-medium tracking-wider mt-0.5">DATOS DE EMERGENCIA / ICE</p>
        </div>
      </div>
      <span class="bg-red-800 text-xs px-2.5 py-1 rounded-full font-semibold uppercase tracking-wider">Urgencias</span>
    </header>

    <div class="p-5 space-y-5">
      <!-- Datos Personales -->
      <section class="flex items-center space-x-4 border-b border-slate-100 pb-4">
        <div class="w-16 h-16 rounded-full bg-slate-100 border border-slate-300 flex items-center justify-center text-slate-400 text-2xl font-bold">
          <i class="fa-solid fa-user"></i>
        </div>
        <div>
          <h2 class="text-xl font-black text-slate-900 leading-tight">César Rea</h2>
          <p class="text-xs text-slate-500 font-medium">Fecha de Nacimiento: 10/04/1994</p>
          <span class="inline-block mt-1 text-[11px] bg-slate-100 text-slate-600 px-2 py-0.5 rounded font-medium">ID / Emergencia</span>
        </div>
      </section>

      <!-- Resumen Crítico (Sangre y Donante) -->
      <section class="grid grid-cols-2 gap-3">
        <div class="bg-red-50 border border-red-200 rounded-2xl p-3 text-center">
          <span class="text-xs text-red-600 font-bold uppercase tracking-wider block">Tipo de Sangre</span>
          <span class="text-3xl font-black text-red-700 tracking-tight">O+</span>
        </div>
        <div class="bg-emerald-50 border border-emerald-200 rounded-2xl p-3 text-center flex flex-col justify-center items-center">
          <span class="text-xs text-emerald-700 font-bold uppercase tracking-wider block">Donante</span>
          <div class="flex items-center space-x-1.5 mt-1">
            <i class="fa-solid fa-circle-check text-emerald-600"></i>
            <span class="text-base font-bold text-emerald-900">SÍ ES DONANTE</span>
          </div>
        </div>
      </section>

      <!-- Alergias y Notas Médicas -->
      <section class="space-y-3">
        <div class="bg-amber-50 border-l-4 border-amber-500 p-3 rounded-r-xl">
          <p class="text-xs font-bold text-amber-800 uppercase tracking-wide flex items-center gap-1.5">
            <i class="fa-solid fa-triangle-exclamation text-amber-600"></i> Alergias Críticas
          </p>
          <p class="text-sm font-semibold text-slate-800 mt-1">Penicilina / Sin alergias reportadas a alimentos</p>
        </div>

        <div class="bg-slate-50 border border-slate-200 p-3 rounded-2xl">
          <p class="text-xs font-bold text-slate-500 uppercase tracking-wide">Padecimientos / Medicación</p>
          <p class="text-sm text-slate-700 font-medium mt-1">Ningún padecimiento crónico actual. No medicado.</p>
        </div>
      </section>

      <!-- Contactos de Emergencia -->
      <section class="pt-2">
        <h3 class="text-xs font-black text-slate-400 uppercase tracking-wider mb-3">Contactos de Emergencia</h3>
        
        <div class="space-y-2.5">
          <!-- Contacto 1 -->
          <div class="p-3 bg-slate-50 border border-slate-200 rounded-2xl flex items-center justify-between">
            <div>
              <p class="font-bold text-slate-900 text-sm leading-snug">Mamá</p>
              <p class="text-xs text-slate-500">Familiar directo</p>
            </div>
            <div class="flex space-x-2">
              <a href="tel:+520000000000" class="w-9 h-9 rounded-full bg-emerald-600 text-white flex items-center justify-center text-sm shadow hover:bg-emerald-700 transition">
                <i class="fa-solid fa-phone"></i>
              </a>
              <a href="https://wa.me/520000000000" target="_blank" class="w-9 h-9 rounded-full bg-emerald-500 text-white flex items-center justify-center text-sm shadow hover:bg-emerald-600 transition">
                <i class="fa-brands fa-whatsapp"></i>
              </a>
            </div>
          </div>

          <!-- Contacto 2 -->
          <div class="p-3 bg-slate-50 border border-slate-200 rounded-2xl flex items-center justify-between">
            <div>
              <p class="font-bold text-slate-900 text-sm leading-snug">Contacto 2</p>
              <p class="text-xs text-slate-500">Amigo / Pareja</p>
            </div>
            <div class="flex space-x-2">
              <a href="tel:+520000000000" class="w-9 h-9 rounded-full bg-emerald-600 text-white flex items-center justify-center text-sm shadow hover:bg-emerald-700 transition">
                <i class="fa-solid fa-phone"></i>
              </a>
              <a href="https://wa.me/520000000000" target="_blank" class="w-9 h-9 rounded-full bg-emerald-500 text-white flex items-center justify-center text-sm shadow hover:bg-emerald-600 transition">
                <i class="fa-brands fa-whatsapp"></i>
              </a>
            </div>
          </div>
        </div>
      </section>
    </div>

    <!-- Pie de página -->
    
    <footer class="bg-slate-50 border-t border-slate-100 p-3 text-center">
      <p class="text-[11px] text-slate-400 font-medium">Ficha de soporte médico ICE para lectura rápida.</p>
    </footer>
  </main>
</body>
</html>
