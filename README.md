<!DOCTYPE html>
<html lang="ko" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>AREXMADO 팬카페 | YouTube 커뮤니티</title>
  <meta name="description" content="AREXMADO 유튜브 팬들을 위한 공식 팬카페: 공지, 최신 영상, 일정, 팬아트, 이벤트, 소통." />
  <meta property="og:title" content="AREXMADO 팬카페" />
  <meta property="og:description" content="공지 · 최신 영상 · 팬아트 · 이벤트 · 소통" />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="./images/og-image.png" />
  <meta name="theme-color" content="#0ea5e9" />
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .card-glow { box-shadow: 0 10px 25px rgba(2,132,199,.15); }
    .hide { display: none; }
    iframe { border-radius: 1.5rem; }
  </style>
</head>
<body class="bg-slate-950 text-slate-100 selection:bg-cyan-400/40">

<!-- 최상단 표시용 제목 -->
<div class="text-center text-3xl font-bold text-white mt-6">
  AREXMADO-Community
</div>

<!-- 헤더 -->
<header class="fixed inset-x-0 top-0 z-50 backdrop-blur bg-slate-900/80 border-b border-slate-800">
  <div class="mx-auto max-w-6xl px-4 py-3 flex items-center gap-4">
    <a href="#top" class="flex items-center gap-2">
      <span class="inline-flex h-8 w-8 items-center justify-center rounded-xl bg-cyan-500 font-bold text-slate-900">A</span>
      <span class="font-semibold">AREXMADO 팬카페</span>
    </a>
    <nav class="ml-auto hidden md:flex gap-5 text-sm text-slate-300">
      <a href="#news" class="hover:text-white">공지</a>
      <a href="#videos" class="hover:text-white">영상</a>
      <a href="#events" class="hover:text-white">이벤트</a>
      <a href="#gallery" class="hover:text-white">팬아트</a>
      <a href="#schedule" class="hover:text-white">일정</a>
      <a href="#community" class="hover:text-white">커뮤니티</a>
      <a href="#faq" class="hover:text-white">FAQ</a>
    </nav>
    <button id="themeToggle" class="ml-4 rounded-xl border border-slate-700 px-3 py-1 text-sm">라이트</button>
  </div>
</header>

<!-- Hero + 유튜브 영상 -->
<section id="top" class="pt-32">
  <div class="mx-auto max-w-6xl px-4">
    <div class="rounded-3xl bg-gradient-to-br from-sky-700/50 via-slate-900 to-slate-900 p-1">
      <div class="rounded-3xl bg-slate-950/70 p-6 md:p-10">
        <div class="grid md:grid-cols-2 gap-8 items-center">
          <div>
            <h1 class="text-3xl md:text-5xl font-extrabold leading-tight">
              AREXMADO 팬카페 & 커뮤니티 허브
            </h1>
            <p class="mt-4 text-slate-300 text-lg">
              유튜브 팬들을 위한 공식 커뮤니티 🎉<br>
              공지, 최신 영상, 팬아트, 이벤트와 소통을 한 곳에서 즐겨보세요.
            </p>
            <div class="mt-6 flex flex-wrap gap-3">
              <a href="#news" class="px-5 py-3 rounded-2xl bg-cyan-500 text-slate-900 font-semibold hover:opacity-90">
                공지 보기
              </a>
              <a href="#community" class="px-5 py-3 rounded-2xl border border-slate-700 hover:bg-slate-800">
                커뮤니티 참여
              </a>
            </div>
          </div>

          <!-- 유튜브 영상 -->
          <div class="relative aspect-video w-full rounded-3xl overflow-hidden shadow-lg">
            <iframe class="w-full h-full"
                    src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
                    title="AREXMADO 유튜브 영상"
                    frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen>
            </iframe>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- 공지 -->
<section id="news" class="max-w-6xl mx-auto px-4 py-16">
  <h2 class="text-2xl md:text-3xl font-bold mb-6">📢 공지사항</h2>
  <ul class="space-y-4">
    <li class="p-5 rounded-2xl bg-slate-900/70 border border-slate-800">
      <div class="text-sm text-slate-400">2025-08-24</div>
      <div class="font-semibold mt-1">AREXMADO 팬카페 오픈 🎊</div>
      <p class="mt-1 text-slate-300">팬 여러분 환영합니다! 앞으로 다양한 이벤트와 소식을 공유할 예정입니다.</p>
    </li>
    <li class="p-5 rounded-2xl bg-slate-900/70 border border-slate-800">
      <div class="text-sm text-slate-400">2025-08-24</div>
      <div class="font-semibold mt-1">구독자 이벤트 개최 조건!</div>
      <p class="mt-1 text-slate-300">유튜브 채널의 구독자 1,000명 이 되면 50개의 동영상을 10년내로 올리겠습니다.</p>
    </li>
    <li class="p-5 rounded-2xl bg-slate-900/70 border border-slate-800">
      <div class="text-sm text-slate-400">2025-08-24</div>
      <div class="font-semibold mt-1">동영상 이벤트</div>
      <p class="mt-1 text-slate-300">동영상을 보고 가장 좋은것을 네이버 펜카페에 올려주시면 제가 가장 많은 표를 받은 글을 추첨해서 앤드카드에 올려드리겠습니다.</p>
    </li>
  </ul>
</section>

<!-- 일정 -->
<section id="schedule" class="max-w-6xl mx-auto px-4 py-16">
  <h2 class="text-2xl md:text-3xl font-bold mb-6">📅 일정</h2>
  <ul class="space-y-4">
    <li class="p-5 rounded-2xl bg-slate-900/70 border border-slate-800">
      <div class="font-semibold">20??년 ?월 ??일</div>
      <p class="text-slate-300">라이브 방송 (Q&A 스트리밍)</p>
    </li>
    <li class="p-5 rounded-2xl bg-slate-900/70 border border-slate-800">
      <div class="font-semibold">2026년 8월 24일</div>
      <p class="text-slate-300">동영상 이벤트 종료</p>
    </li>
  </ul>
</section>

<!-- 커뮤니티 -->
<section id="community" class="max-w-6xl mx-auto px-4 py-16">
  <h2 class="text-2xl md:text-3xl font-bold mb-6">💬 커뮤니티</h2>
  <div class="grid md:grid-cols-4 gap-6">
    <a href="https://www.youtube.com/@arexmado" target="_blank" class="p-6 rounded-2xl bg-slate-900/70 border border-slate-800 hover:bg-slate-800">📺 YouTube 채널</a>
    <a href="https://cafe.naver.com/arex" target="_blank" class="p-6 rounded-2xl bg-slate-900/70 border border-slate-800 hover:bg-slate-800">🏠 네이버 팬카페</a>
    <a href="https://discord.gg/XKmYrcWu" target="_blank" class="p-6 rounded-2xl bg-slate-900/70 border border-slate-800 hover:bg-slate-800">🎮 Discord 서버</a>
    <a href="https://afreecatv.com/soop" target="_blank" class="p-6 rounded-2xl bg-slate-900/70 border border-slate-800 hover:bg-slate-800">📡 Soop 아프리카TV</a>
  </div>
</section>

<!-- FAQ -->
<section id="faq" class="max-w-6xl mx-auto px-4 py-16">
  <h2 class="text-2xl md:text-3xl font-bold mb-6">❓ FAQ</h2>
  <div class="space-y-4">
    <details class="rounded-2xl bg-slate-900/70 border border-slate-800 p-4">
      <summary class="cursor-pointer font-semibold">가입은 어떻게 하나요?</summary>
      <p class="mt-2 text-slate-300">이 사이트 자체는 정적 사이트라 가입 기능이 없습니다. 팬카페 또는 Discord 서버에서 가입하실 수 있습니다.</p>
    </details>
    <details class="rounded-2xl bg-slate-900/70 border border-slate-800 p-4">
      <summary class="cursor-pointer font-semibold">이벤트 소식은 어디서 확인하나요?</summary>
      <p class="mt-2 text-slate-300">공지사항 섹션과 유튜브 커뮤니티, 팬카페 공지, Soop(아프리카) 게시판을 확인해주세요.</p>
    </details>
    <details class="rounded-2xl bg-slate-900/70 border border-slate-800 p-4">
      <summary class="cursor-pointer font-semibold">사이트의 불편한점 기재하는법은 무었인가요?</summary>
      <p class="mt-2 text-slate-300">이메일 기재는 사이트의 끝에서 확인할 수 있습니다.</p>
    </details>
  </div>
</section>

<!-- 푸터 -->
<footer class="border-t border-slate-800 py-10 text-center text-sm text-slate-500 space-y-2">
  <div>© 2025 AREXMADO Community. All rights reserved.</div>
  <div>문의: <a href="mailto:arexmado@example.com" class="text-cyan-500 hover:underline">arexmado@gmail.com</a></div>
</footer>

<script>
  // 라이트/다크 모드 토글
  const themeBtn = document.getElementById("themeToggle");
  themeBtn.addEventListener("click", () => {
    document.body.classList.toggle("bg-slate-950");
    document.body.classList.toggle("text-slate-100");
    document.body.classList.toggle("bg-white");
    document.body.classList.toggle("text-slate-900");

    // 각 섹션 카드 배경 토글
    document.querySelectorAll('section, footer, details').forEach(el => {
      el.classList.toggle('bg-slate-950/70');
      el.classList.toggle('bg-white/70');
      el.classList.toggle('border-slate-800');
      el.classList.toggle('border-slate-300');
    });

    // 버튼 텍스트 변경
    themeBtn.textContent = themeBtn.textContent === "라이트" ? "다크" : "라이트";
  });

  // 스크롤에 따라 헤더 숨김/등장
  const header = document.querySelector("header");
  let lastScroll = 0;
  window.addEventListener("scroll", () => {
    let currentScroll = window.pageYOffset;
    if (currentScroll > lastScroll && currentScroll > 50) {
      header.style.transform = "translateY(-100%)";
    } else {
      header.style.transform = "translateY(0)";
    }
    lastScroll = currentScroll;
  });
</script>

</body>
</html>
