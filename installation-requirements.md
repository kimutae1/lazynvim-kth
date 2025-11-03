# LazyVim 설치 요구사항

## ✅ 설치 완료된 항목
- **Neovim**: v0.11.5 (✓ 0.9.0+ 요구사항 충족)
- **Git**: v2.43.0 (✓)
- **Node.js**: v21.7.3 (✓ LSP 서버용)
- **Python**: v3.12.3 (✓ Python LSP용)
- **Ripgrep**: v14.1.0 (✓ Telescope 검색용)
- **Lazygit**: v0.45.0 (✓ Git UI용)

## ❌ 설치 필요한 항목

### 필수 도구
- **fd**: 빠른 파일 검색을 위한 도구 (Telescope에서 사용)
  ```bash
  # Ubuntu/Debian
  sudo apt install fd-find
  
  # 또는 snap
  sudo snap install fd
  ```

### 권장 도구 (선택사항)
- **Nerd Font**: 아이콘 표시를 위한 폰트
  - JetBrains Mono Nerd Font 권장
  - [다운로드 링크](https://www.nerdfonts.com/font-downloads)

## 📝 설정 상태
- LazyVim 기본 설정 완료
- 플러그인 예제 파일 존재 (비활성화 상태)
- Mason을 통한 LSP 서버 자동 설치 설정됨

## 🚀 다음 단계
1. `fd` 설치
2. Nerd Font 설치 및 터미널 폰트 설정
3. `nvim` 실행하여 플러그인 자동 설치 확인
