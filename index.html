<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>G X P ARXHIVE</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- FontAwesome Icons CDN -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <!-- Inter & Noto Sans KR Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;700&family=Noto+Sans+KR:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              gold: '#E6CA65',
              goldHover: '#D4B95E',
              goldDark: '#8F7C38',
              bg: '#121214',
              surface: '#1A1A1E',
              card: '#222227',
              border: '#32323A',
              muted: '#9E9EA0'
            }
          },
          fontFamily: {
            title: ['Cinzel', 'serif'],
            sans: ['Noto Sans KR', 'sans-serif']
          }
        }
      }
    }
  </script>
  <style>
    body {
      background-color: #121214;
      color: #E2E2E8;
      font-family: 'Noto Sans KR', sans-serif;
    }
    .custom-scrollbar::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    .custom-scrollbar::-webkit-scrollbar-track {
      background: #1A1A1E;
    }
    .custom-scrollbar::-webkit-scrollbar-thumb {
      background: #32323A;
      border-radius: 3px;
    }
    .custom-scrollbar::-webkit-scrollbar-thumb:hover {
      background: #8F7C38;
    }
    .art-card-glow {
      transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1);
    }
    .art-card-glow:hover {
      box-shadow: 0 10px 30px -10px rgba(230, 202, 101, 0.15);
      border-color: rgba(230, 202, 101, 0.4);
      transform: translateY(-4px);
    }
  </style>
</head>
<body class="min-h-screen flex flex-col bg-brand-bg text-gray-200">

  <!-- Header -->
  <header class="sticky top-0 z-30 bg-brand-bg/90 backdrop-blur-md border-b border-brand-border/60 transition-all">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-20">
        
        <!-- Logo & Branding -->
        <div class="flex items-center space-x-4 cursor-pointer" onclick="resetFilters()">
          <div class="relative w-11 h-11 rounded-xl bg-gradient-to-br from-brand-card to-brand-surface border border-brand-gold/30 flex items-center justify-center text-brand-gold shadow-md">
            <!-- 만년필 & 장미 커스텀 아이콘 -->
            <i class="fa-solid fa-pen-nib text-lg transform -rotate-45 translate-x-[-2px] translate-y-[-1px]"></i>
            <svg class="w-3.5 h-3.5 text-brand-gold absolute bottom-1 right-1 opacity-90 fill-current" viewBox="0 0 24 24">
              <path d="M12 2C9 2 7 3.5 7 5.5c0 1.2.6 2.3 1.6 3-1.6.4-2.6 1.6-2.6 3 0 1.8 1.8 3.5 4 3.5.5 0 1-.1 1.5-.3C10.5 16 9 18 9 20c0 1.1.9 2 2 2s2-.9 2-2c0-2-1.5-4-2.5-5.3.5.2 1 .3 1.5.3 2.2 0 4-1.7 4-3.5 0-1.4-1-2.6-2.6-3 1-.7 1.6-1.8 1.6-3C17 3.5 15 2 12 2z"/>
            </svg>
          </div>
          <div>
            <h1 class="text-xl sm:text-2xl font-bold tracking-wider font-title text-brand-gold flex items-center gap-2">
              G X P ARXHIVE
            </h1>
            <p class="text-xs text-brand-muted tracking-tight font-medium">
              &gt; 계피 커미션 보관함
            </p>
          </div>
        </div>

        <!-- Right Header Actions (스크린샷 버튼 스타일) -->
        <div class="flex items-center space-x-3">
          <button onclick="openAddModal()" class="px-4 py-2 text-xs sm:text-sm font-semibold text-brand-bg bg-brand-gold hover:bg-brand-goldHover rounded-lg shadow-lg shadow-brand-gold/10 transition-all flex items-center gap-2">
            <i class="fa-solid fa-feather text-sm"></i>
            <span>작품 등록</span>
          </button>

          <button onclick="exportData()" class="px-3.5 py-2 text-xs font-medium text-gray-300 hover:text-brand-gold bg-brand-card border border-brand-border hover:border-brand-gold/40 rounded-lg transition-all flex items-center gap-2">
            <i class="fa-solid fa-download"></i>
            <span class="hidden sm:inline">백업</span>
          </button>

          <button onclick="document.getElementById('importFileInput').click()" class="px-3.5 py-2 text-xs font-medium text-gray-300 hover:text-brand-gold bg-brand-card border border-brand-border hover:border-brand-gold/40 rounded-lg transition-all flex items-center gap-2">
            <i class="fa-solid fa-upload"></i>
            <span class="hidden sm:inline">복원</span>
          </button>
          <input type="file" id="importFileInput" accept=".json" class="hidden" onchange="importData(event)">
        </div>

      </div>
    </div>
  </header>

  <!-- Main Content Area -->
  <main class="flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-8">
    
    <!-- Controls Box (검색창 + 필터 버튼 + 정렬) -->
    <div class="bg-brand-surface/80 border border-brand-border/60 rounded-2xl p-4 sm:p-5 mb-8 shadow-xl">
      <!-- 상단: 검색창 & 카테고리 알약 탭 -->
      <div class="flex flex-col lg:flex-row gap-4 justify-between items-stretch lg:items-center pb-4 border-b border-brand-border/40">
        
        <!-- Search Bar -->
        <div class="relative flex-1 max-w-md">
          <i class="fa-solid fa-magnifying-glass absolute left-4 top-1/2 -translate-y-1/2 text-brand-muted text-sm"></i>
          <input type="text" id="searchInput" placeholder="제목, 작가명, 태그 검색..." oninput="handleSearch()" class="w-full bg-brand-bg/80 text-sm text-gray-200 placeholder-brand-muted border border-brand-border rounded-xl pl-11 pr-10 py-2.5 focus:outline-none focus:border-brand-gold/70 transition-all">
          <button id="clearSearchBtn" onclick="clearSearch()" class="hidden absolute right-3 top-1/2 -translate-y-1/2 text-brand-muted hover:text-gray-200 p-1">
            <i class="fa-solid fa-xmark text-xs"></i>
          </button>
        </div>

        <!-- Category Pill Buttons (스크린샷 스타일) -->
        <div class="flex items-center gap-2 overflow-x-auto pb-1 lg:pb-0 custom-scrollbar" id="categoryPillGroup">
          <button onclick="setCategoryFilter('ALL')" data-category="ALL" class="pill-btn active px-4 py-1.5 rounded-full text-xs font-semibold border transition-all bg-brand-gold/20 text-brand-gold border-brand-gold/50">전체보기</button>
          <button onclick="setCategoryFilter('일러스트')" data-category="일러스트" class="pill-btn px-4 py-1.5 rounded-full text-xs font-medium border transition-all bg-brand-card hover:bg-brand-border text-gray-300 border-brand-border">일러스트</button>
          <button onclick="setCategoryFilter('캐릭터')" data-category="캐릭터" class="pill-btn px-4 py-1.5 rounded-full text-xs font-medium border transition-all bg-brand-card hover:bg-brand-border text-gray-300 border-brand-border">캐릭터</button>
          <button onclick="setCategoryFilter('SD')" data-category="SD" class="pill-btn px-4 py-1.5 rounded-full text-xs font-medium border transition-all bg-brand-card hover:bg-brand-border text-gray-300 border-brand-border">SD</button>
          <button onclick="setCategoryFilter('외주/상업')" data-category="외주/상업" class="pill-btn px-4 py-1.5 rounded-full text-xs font-medium border transition-all bg-brand-card hover:bg-brand-border text-gray-300 border-brand-border">외주/상업</button>
          <button onclick="setCategoryFilter('기타')" data-category="기타" class="pill-btn px-4 py-1.5 rounded-full text-xs font-medium border transition-all bg-brand-card hover:bg-brand-border text-gray-300 border-brand-border">기타</button>
        </div>

      </div>

      <!-- 하단: 개수 수량 + 보기 모드 아이콘 + 정렬 선택 -->
      <div class="flex items-center justify-between pt-4 text-xs text-brand-muted">
        <div>
          보관중인 작품 <span id="artCount" class="text-brand-gold font-bold">0</span>개
        </div>

        <div class="flex items-center gap-4">
          <!-- 보기 모드 아이콘 -->
          <div class="flex items-center gap-2">
            <span>보기</span>
            <div class="flex items-center bg-brand-bg border border-brand-border rounded-lg p-1 gap-1">
              <button onclick="setGridSize('lg')" id="gridLgBtn" class="p-1.5 rounded text-brand-gold bg-brand-card" title="4열 보기">
                <i class="fa-solid fa-table-cells-large"></i>
              </button>
              <button onclick="setGridSize('md')" id="gridMdBtn" class="p-1.5 rounded text-brand-muted hover:text-gray-200" title="3열 보기">
                <i class="fa-solid fa-border-all"></i>
              </button>
              <button onclick="setGridSize('sm')" id="gridSmBtn" class="p-1.5 rounded text-brand-muted hover:text-gray-200" title="2열 보기">
                <i class="fa-solid fa-square"></i>
              </button>
            </div>
          </div>

          <!-- Sort Select -->
          <div class="flex items-center gap-2">
            <span>정렬</span>
            <select id="sortSelect" onchange="applyFilters()" class="bg-brand-bg border border-brand-border text-xs text-gray-300 rounded-lg px-3 py-1.5 focus:outline-none focus:border-brand-gold/70 cursor-pointer">
              <option value="NEWEST">최신 등록순</option>
              <option value="OLDEST">오래된 순</option>
              <option value="TITLE">제목순</option>
            </select>
          </div>
        </div>

      </div>
    </div>

    <!-- Gallery Grid -->
    <div id="galleryGrid" class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
      <!-- Art Cards Will Be Injected Here -->
    </div>

    <!-- Empty State -->
    <div id="emptyState" class="hidden py-24 text-center">
      <div class="w-16 h-16 mx-auto mb-4 rounded-2xl bg-brand-surface border border-brand-border flex items-center justify-center text-brand-muted text-2xl">
        <i class="fa-solid fa-box-open"></i>
      </div>
      <h3 class="text-base font-semibold text-gray-300">보관된 작품이 없습니다</h3>
      <p class="text-xs text-brand-muted mt-1 max-w-sm mx-auto">상단의 '작품 등록' 버튼을 눌러 소중한 커미션 이미지를 보관해 보세요.</p>
    </div>

  </main>

  <!-- Footer -->
  <footer class="border-t border-brand-border/40 py-8 text-center text-xs text-brand-muted">
    <div class="max-w-7xl mx-auto px-4">
      <p>© G X P ARXHIVE. 계피 커미션 보관함.</p>
    </div>
  </footer>

  <!-- 1. ADD / EDIT ARTWORK MODAL -->
  <div id="artModal" class="fixed inset-0 z-50 hidden bg-black/80 backdrop-blur-sm flex items-center justify-center p-4 overflow-y-auto">
    <div class="bg-brand-surface border border-brand-border w-full max-w-lg rounded-2xl p-6 shadow-2xl my-8 relative">
      <div class="flex items-center justify-between pb-4 border-b border-brand-border">
        <h2 id="modalTitle" class="text-lg font-bold text-brand-gold">새 커미션 작품 등록</h2>
        <button onclick="closeAddModal()" class="text-brand-muted hover:text-gray-200 p-1">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>

      <form id="artForm" onsubmit="handleFormSubmit(event)" class="mt-5 space-y-4">
        <input type="hidden" id="artId">

        <!-- Image Upload Area -->
        <div>
          <label class="block text-xs font-semibold text-gray-300 mb-1.5">작품 이미지 *</label>
          <div class="relative border-2 border-dashed border-brand-border hover:border-brand-gold/60 rounded-xl p-4 text-center cursor-pointer transition-all bg-brand-bg/50" onclick="document.getElementById('imageInput').click()">
            <input type="file" id="imageInput" accept="image/*" class="hidden" onchange="previewImage(event)">
            
            <div id="uploadPlaceholder" class="py-4">
              <i class="fa-solid fa-cloud-arrow-up text-2xl text-brand-gold/70 mb-2"></i>
              <p class="text-xs text-gray-300">클릭하여 이미지 업로드</p>
              <p class="text-[11px] text-brand-muted mt-0.5">PNG, JPG, WEBP 지원</p>
            </div>

            <div id="imagePreviewContainer" class="hidden relative rounded-lg overflow-hidden border border-brand-border max-h-48">
              <img id="imagePreview" class="w-full h-48 object-cover">
            </div>
          </div>
        </div>

        <!-- Title & Artist -->
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
          <div>
            <label class="block text-xs font-semibold text-gray-300 mb-1">작품 제목 *</label>
            <input type="text" id="artTitle" required placeholder="예: 나나곰 바게트" class="w-full bg-brand-bg border border-brand-border rounded-lg p-2.5 text-xs text-gray-200 focus:outline-none focus:border-brand-gold">
          </div>
          <div>
            <label class="block text-xs font-semibold text-gray-300 mb-1">작가 / 커미션주 *</label>
            <input type="text" id="artArtist" required placeholder="예: 나나곰" class="w-full bg-brand-bg border border-brand-border rounded-lg p-2.5 text-xs text-gray-200 focus:outline-none focus:border-brand-gold">
          </div>
        </div>

        <!-- Category & Date -->
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
          <div>
            <label class="block text-xs font-semibold text-gray-300 mb-1">카테고리</label>
            <select id="artCategory" class="w-full bg-brand-bg border border-brand-border rounded-lg p-2.5 text-xs text-gray-200 focus:outline-none focus:border-brand-gold">
              <option value="일러스트">일러스트</option>
              <option value="캐릭터">캐릭터</option>
              <option value="SD">SD</option>
              <option value="외주/상업">외주/상업</option>
              <option value="기타">기타</option>
            </select>
          </div>
          <div>
            <label class="block text-xs font-semibold text-gray-300 mb-1">수령일자</label>
            <input type="date" id="artDate" class="w-full bg-brand-bg border border-brand-border rounded-lg p-2.5 text-xs text-gray-200 focus:outline-none focus:border-brand-gold">
          </div>
        </div>

        <!-- Tags & Link -->
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
          <div>
            <label class="block text-xs font-semibold text-gray-300 mb-1">태그 (쉼표 구분)</label>
            <input type="text" id="artTags" placeholder="예: 자캐, 흑발, 몽환적" class="w-full bg-brand-bg border border-brand-border rounded-lg p-2.5 text-xs text-gray-200 focus:outline-none focus:border-brand-gold">
          </div>
          <div>
            <label class="block text-xs font-semibold text-gray-300 mb-1">출처 링크</label>
            <input type="url" id="artLink" placeholder="https://x.com/..." class="w-full bg-brand-bg border border-brand-border rounded-lg p-2.5 text-xs text-gray-200 focus:outline-none focus:border-brand-gold">
          </div>
        </div>

        <!-- Memo -->
        <div>
          <label class="block text-xs font-semibold text-gray-300 mb-1">메모 / 요청 사항</label>
          <textarea id="artMemo" rows="2" placeholder="참고할 메모를 적어주세요." class="w-full bg-brand-bg border border-brand-border rounded-lg p-2.5 text-xs text-gray-200 focus:outline-none focus:border-brand-gold resize-none"></textarea>
        </div>

        <!-- Submit Button -->
        <div class="pt-2 flex justify-end gap-2">
          <button type="button" onclick="closeAddModal()" class="px-4 py-2 text-xs font-medium text-gray-400 hover:text-gray-200 bg-brand-card rounded-lg">취소</button>
          <button type="submit" class="px-5 py-2 text-xs font-semibold text-brand-bg bg-brand-gold hover:bg-brand-goldHover rounded-lg transition-all">저장하기</button>
        </div>
      </form>
    </div>
  </div>

  <!-- 2. LIGHTBOX / DETAIL VIEW MODAL -->
  <div id="lightboxModal" class="fixed inset-0 z-50 hidden bg-black/95 backdrop-blur-md flex items-center justify-center p-2 sm:p-6">
    <div class="relative w-full max-w-5xl h-full max-h-[92vh] bg-brand-surface border border-brand-border/80 rounded-2xl overflow-hidden flex flex-col md:flex-row">
      
      <!-- Close Button -->
      <button onclick="closeLightbox()" class="absolute top-4 right-4 z-20 bg-black/60 text-gray-300 hover:text-white w-9 h-9 rounded-full flex items-center justify-center backdrop-blur-sm border border-white/10 transition-all">
        <i class="fa-solid fa-xmark text-base"></i>
      </button>

      <!-- Image Display Area -->
      <div class="flex-1 bg-black/80 flex items-center justify-center p-4 relative overflow-hidden min-h-[300px]">
        <img id="lightboxImage" class="max-w-full max-h-full object-contain rounded-md shadow-2xl">
      </div>

      <!-- Detail Info Drawer Area -->
      <div class="w-full md:w-80 lg:w-96 bg-brand-surface border-t md:border-t-0 md:border-l border-brand-border p-6 flex flex-col justify-between overflow-y-auto custom-scrollbar">
        <div>
          <div class="flex items-center gap-2 mb-2">
            <span id="lightboxCategory" class="px-2.5 py-0.5 rounded-md text-[11px] font-medium bg-brand-gold/10 text-brand-gold border border-brand-gold/30"></span>
            <span id="lightboxDate" class="text-xs text-brand-muted"></span>
          </div>

          <h2 id="lightboxTitle" class="text-xl font-bold text-gray-100 mb-1"></h2>
          
          <div class="flex items-center gap-2 text-xs text-brand-gold/90 mb-6">
            <i class="fa-regular fa-user"></i>
            <span id="lightboxArtist" class="font-medium"></span>
            <a id="lightboxLink" href="#" target="_blank" class="hidden text-brand-muted hover:text-brand-gold text-xs ml-1">
              <i class="fa-solid fa-arrow-up-right-from-square"></i>
            </a>
          </div>

          <!-- Tags -->
          <div class="mb-6">
            <h4 class="text-[11px] uppercase tracking-wider font-semibold text-brand-muted mb-2">태그</h4>
            <div id="lightboxTags" class="flex flex-wrap gap-1.5"></div>
          </div>

          <!-- Memo -->
          <div class="mb-6">
            <h4 class="text-[11px] uppercase tracking-wider font-semibold text-brand-muted mb-2">메모</h4>
            <div id="lightboxMemo" class="text-xs text-gray-300 bg-brand-bg border border-brand-border rounded-xl p-3 min-h-[60px] whitespace-pre-wrap leading-relaxed"></div>
          </div>
        </div>

        <!-- Action Buttons -->
        <div class="pt-4 border-t border-brand-border flex items-center justify-between gap-2">
          <a id="downloadBtn" download class="flex-1 py-2.5 bg-brand-card hover:bg-brand-border text-gray-200 text-xs font-semibold rounded-xl text-center transition-all border border-brand-border flex items-center justify-center gap-2">
            <i class="fa-solid fa-download text-xs"></i>
            <span>다운로드</span>
          </a>
          
          <button id="editBtn" class="px-3 py-2.5 bg-brand-card hover:bg-brand-border text-gray-300 text-xs rounded-xl border border-brand-border transition-all">
            <i class="fa-solid fa-pen"></i>
          </button>
          
          <button id="deleteBtn" class="px-3 py-2.5 bg-red-950/40 hover:bg-red-900/60 text-red-400 text-xs rounded-xl border border-red-900/50 transition-all">
            <i class="fa-solid fa-trash-can"></i>
          </button>
        </div>

      </div>

    </div>
  </div>

  <!-- JavaScript Logic -->
  <script>
    const STORAGE_KEY = 'gxp_arxhive_data';
    let artList = [];
    let currentFilteredList = [];
    let selectedCategory = 'ALL';
    let selectedImageBase64 = '';

    // Sample data to initialize if empty
    const SAMPLE_DATA = [
      {
        id: 'sample_1',
        title: '나나곰 바게트',
        artist: '나나곰',
        category: '일러스트',
        date: '2026-10-23',
        tags: ['귀여운', '체크패턴', '바게트'],
        memo: '나나곰 님의 바게트 일러스트 커미션입니다.',
        image: 'https://images.unsplash.com/photo-1579783902614-a3fb3927b675?auto=format&fit=crop&w=600&q=80',
        createdAt: Date.now()
      }
    ];

    document.addEventListener('DOMContentLoaded', () => {
      loadArtData();
      renderGallery();
    });

    function loadArtData() {
      const storedData = localStorage.getItem(STORAGE_KEY);
      if (storedData) {
        try {
          artList = JSON.parse(storedData);
        } catch (e) {
          artList = SAMPLE_DATA;
        }
      } else {
        artList = SAMPLE_DATA;
      }
    }

    function saveArtData() {
      localStorage.setItem(STORAGE_KEY, JSON.stringify(artList));
      applyFilters();
    }

    function renderGallery(items = currentFilteredList) {
      const grid = document.getElementById('galleryGrid');
      const emptyState = document.getElementById('emptyState');
      const artCount = document.getElementById('artCount');

      artCount.innerText = items.length;
      grid.innerHTML = '';

      if (items.length === 0) {
        grid.classList.add('hidden');
        emptyState.classList.remove('hidden');
        return;
      }

      grid.classList.remove('hidden');
      emptyState.classList.add('hidden');

      items.forEach(item => {
        const card = document.createElement('div');
        card.className = `art-card-glow bg-brand-surface border border-brand-border/80 rounded-2xl overflow-hidden cursor-pointer flex flex-col group`;
        card.onclick = () => openLightbox(item.id);

        card.innerHTML = `
          <div class="relative aspect-square bg-black/40 overflow-hidden">
            <img src="${item.image}" alt="${item.title}" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" loading="lazy">
            <div class="absolute top-3 left-3">
              <span class="px-2.5 py-1 text-[10px] font-semibold rounded-md bg-black/70 text-brand-gold border border-brand-gold/30 backdrop-blur-md">
                ${item.category || '기타'}
              </span>
            </div>
          </div>
          <div class="p-4 flex flex-col justify-between bg-gradient-to-b from-brand-surface to-brand-card/40">
            <div>
              <h3 class="font-bold text-sm text-gray-200 group-hover:text-brand-gold transition-colors truncate">${escapeHtml(item.title)}</h3>
              <p class="text-xs text-brand-muted mt-1 truncate flex items-center gap-1">
                <i class="fa-regular fa-user text-[10px] text-brand-goldDark"></i>
                <span>${escapeHtml(item.artist)}</span>
              </p>
            </div>
          </div>
        `;

        grid.appendChild(card);
      });
    }

    function applyFilters() {
      const searchVal = document.getElementById('searchInput').value.toLowerCase().trim();
      const sortVal = document.getElementById('sortSelect').value;

      let result = [...artList];

      if (selectedCategory !== 'ALL') {
        result = result.filter(item => item.category === selectedCategory);
      }

      if (searchVal) {
        result = result.filter(item => 
          item.title.toLowerCase().includes(searchVal) ||
          item.artist.toLowerCase().includes(searchVal) ||
          (item.tags && item.tags.some(t => t.toLowerCase().includes(searchVal)))
        );
      }

      if (sortVal === 'NEWEST') {
        result.sort((a, b) => b.createdAt - a.createdAt);
      } else if (sortVal === 'OLDEST') {
        result.sort((a, b) => a.createdAt - b.createdAt);
      } else if (sortVal === 'TITLE') {
        result.sort((a, b) => a.title.localeCompare(b.title));
      }

      currentFilteredList = result;
      renderGallery(currentFilteredList);
    }

    function setCategoryFilter(category) {
      selectedCategory = category;
      const pills = document.querySelectorAll('#categoryPillGroup .pill-btn');
      pills.forEach(btn => {
        if (btn.getAttribute('data-category') === category) {
          btn.className = 'pill-btn active px-4 py-1.5 rounded-full text-xs font-semibold border transition-all bg-brand-gold/20 text-brand-gold border-brand-gold/50';
        } else {
          btn.className = 'pill-btn px-4 py-1.5 rounded-full text-xs font-medium border transition-all bg-brand-card hover:bg-brand-border text-gray-300 border-brand-border';
        }
      });
      applyFilters();
    }

    function handleSearch() {
      const val = document.getElementById('searchInput').value;
      const clearBtn = document.getElementById('clearSearchBtn');
      if (val) clearBtn.classList.remove('hidden');
      else clearBtn.classList.add('hidden');
      applyFilters();
    }

    function clearSearch() {
      document.getElementById('searchInput').value = '';
      document.getElementById('clearSearchBtn').classList.add('hidden');
      applyFilters();
    }

    function resetFilters() {
      document.getElementById('searchInput').value = '';
      document.getElementById('sortSelect').value = 'NEWEST';
      setCategoryFilter('ALL');
    }

    function setGridSize(size) {
      const grid = document.getElementById('galleryGrid');
      const lgBtn = document.getElementById('gridLgBtn');
      const mdBtn = document.getElementById('gridMdBtn');
      const smBtn = document.getElementById('gridSmBtn');

      lgBtn.className = 'p-1.5 rounded text-brand-muted hover:text-gray-200';
      mdBtn.className = 'p-1.5 rounded text-brand-muted hover:text-gray-200';
      smBtn.className = 'p-1.5 rounded text-brand-muted hover:text-gray-200';

      if (size === 'lg') {
        grid.className = 'grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6';
        lgBtn.className = 'p-1.5 rounded text-brand-gold bg-brand-card';
      } else if (size === 'md') {
        grid.className = 'grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6';
        mdBtn.className = 'p-1.5 rounded text-brand-gold bg-brand-card';
      } else {
        grid.className = 'grid grid-cols-1 sm:grid-cols-2 gap-6';
        smBtn.className = 'p-1.5 rounded text-brand-gold bg-brand-card';
      }
    }

    function previewImage(event) {
      const file = event.target.files[0];
      if (!file) return;

      const reader = new FileReader();
      reader.onload = function(e) {
        selectedImageBase64 = e.target.result;
        document.getElementById('imagePreview').src = selectedImageBase64;
        document.getElementById('imagePreviewContainer').classList.remove('hidden');
        document.getElementById('uploadPlaceholder').classList.add('hidden');
      };
      reader.readAsDataURL(file);
    }

    function openAddModal(editId = null) {
      const modal = document.getElementById('artModal');
      const form = document.getElementById('artForm');
      modal.classList.remove('hidden');

      if (editId) {
        const item = artList.find(a => a.id === editId);
        if (!item) return;

        document.getElementById('modalTitle').innerText = '작품 정보 수정';
        document.getElementById('artId').value = item.id;
        document.getElementById('artTitle').value = item.title;
        document.getElementById('artArtist').value = item.artist;
        document.getElementById('artCategory').value = item.category || '기타';
        document.getElementById('artDate').value = item.date || '';
        document.getElementById('artTags').value = item.tags ? item.tags.join(', ') : '';
        document.getElementById('artLink').value = item.link || '';
        document.getElementById('artMemo').value = item.memo || '';

        selectedImageBase64 = item.image;
        document.getElementById('imagePreview').src = item.image;
        document.getElementById('imagePreviewContainer').classList.remove('hidden');
        document.getElementById('uploadPlaceholder').classList.add('hidden');
      } else {
        document.getElementById('modalTitle').innerText = '새 커미션 작품 등록';
        form.reset();
        document.getElementById('artId').value = '';
        selectedImageBase64 = '';
        document.getElementById('imagePreviewContainer').classList.add('hidden');
        document.getElementById('uploadPlaceholder').classList.remove('hidden');
      }
    }

    function closeAddModal() {
      document.getElementById('artModal').classList.add('hidden');
    }

    function handleFormSubmit(event) {
      event.preventDefault();

      if (!selectedImageBase64) {
        alert('이미지를 업로드해 주세요.');
        return;
      }

      const idVal = document.getElementById('artId').value;
      const title = document.getElementById('artTitle').value.trim();
      const artist = document.getElementById('artArtist').value.trim();
      const category = document.getElementById('artCategory').value;
      const date = document.getElementById('artDate').value;
      const rawTags = document.getElementById('artTags').value;
      const link = document.getElementById('artLink').value.trim();
      const memo = document.getElementById('artMemo').value.trim();

      const tags = rawTags.split(',').map(t => t.trim().replace(/^#/, '')).filter(t => t.length > 0);

      if (idVal) {
        const index = artList.findIndex(a => a.id === idVal);
        if (index !== -1) {
          artList[index] = { ...artList[index], title, artist, category, date, tags, link, memo, image: selectedImageBase64 };
        }
      } else {
        const newItem = {
          id: 'art_' + Date.now(),
          title,
          artist,
          category,
          date,
          tags,
          link,
          memo,
          image: selectedImageBase64,
          createdAt: Date.now()
        };
        artList.unshift(newItem);
      }

      saveArtData();
      closeAddModal();
    }

    function openLightbox(id) {
      const item = artList.find(a => a.id === id);
      if (!item) return;

      document.getElementById('lightboxImage').src = item.image;
      document.getElementById('lightboxTitle').innerText = item.title;
      document.getElementById('lightboxArtist').innerText = item.artist;
      document.getElementById('lightboxCategory').innerText = item.category || '기타';
      document.getElementById('lightboxDate').innerText = item.date ? item.date + ' 수령' : '';
      document.getElementById('lightboxMemo').innerText = item.memo || '등록된 메모가 없습니다.';

      const downloadBtn = document.getElementById('downloadBtn');
      downloadBtn.href = item.image;
      downloadBtn.download = `${item.title}_${item.artist}.png`;

      const linkEl = document.getElementById('lightboxLink');
      if (item.link) {
        linkEl.href = item.link;
        linkEl.classList.remove('hidden');
      } else {
        linkEl.classList.add('hidden');
      }

      const tagsContainer = document.getElementById('lightboxTags');
      tagsContainer.innerHTML = '';
      if (item.tags && item.tags.length > 0) {
        item.tags.forEach(tag => {
          const badge = document.createElement('span');
          badge.className = 'text-xs bg-brand-bg text-brand-gold border border-brand-border px-2.5 py-1 rounded-lg';
          badge.innerText = '#' + tag;
          tagsContainer.appendChild(badge);
        });
      } else {
        tagsContainer.innerHTML = '<span class="text-xs text-brand-muted">태그 없음</span>';
      }

      document.getElementById('editBtn').onclick = () => {
        closeLightbox();
        openAddModal(item.id);
      };

      document.getElementById('deleteBtn').onclick = () => {
        if (confirm('이 작품을 삭제하시겠습니까?')) {
          artList = artList.filter(a => a.id !== item.id);
          saveArtData();
          closeLightbox();
        }
      };

      document.getElementById('lightboxModal').classList.remove('hidden');
    }

    function closeLightbox() {
      document.getElementById('lightboxModal').classList.add('hidden');
    }

    function exportData() {
      if (artList.length === 0) {
        alert('백업할 작품 데이터가 없습니다.');
        return;
      }

      const dataStr = "data:text/json;charset=utf-8," + encodeURIComponent(JSON.stringify(artList, null, 2));
      const downloadAnchor = document.createElement('a');
      downloadAnchor.setAttribute("href", dataStr);
      downloadAnchor.setAttribute("download", `GXP_ARXHIVE_BACKUP_${new Date().toISOString().slice(0,10)}.json`);
      document.body.appendChild(downloadAnchor);
      downloadAnchor.click();
      downloadAnchor.remove();
    }

    function importData(event) {
      const file = event.target.files[0];
      if (!file) return;

      const reader = new FileReader();
      reader.onload = function(e) {
        try {
          const importedList = JSON.parse(e.target.result);
          if (Array.isArray(importedList)) {
            if (confirm(`복원 데이터(${importedList.length}개)를 불러오시겠습니까?`)) {
              artList = importedList;
              saveArtData();
              alert('성공적으로 복원되었습니다.');
            }
          }
        } catch (err) {
          alert('JSON 파일을 확인해 주세요.');
        }
      };
      reader.readAsText(file);
    }

    function escapeHtml(text) {
      if (!text) return '';
      return text.replace(/&/g, "&amp;").replace(/</g, "&lt;").replace(/>/g, "&gt;").replace(/"/g, "&quot;").replace(/'/g, "&#039;");
    }
  </script>
</body>
</html>
