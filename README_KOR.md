2019.08.02 Jlsca 사용 방법

# Windows 설치 방법

1. Julia 설치 및 확인
 * https://julialang.org 접속하여 Windows 64bit용 실행파일(julia-1.1.1-win64.exe) 다운 및 설치
   - Julia 설치 경로 예시 (I:\Julia-1.1.1)
 * 환경 변수 PATH 설정 (시스템 속성 > 환경 변수 > 시스템 변수 > path > I:\Julia-1.1.1\bin 추가)
 * CMD 창에서 julia 입력하여 프로그램이 실행되는지 확인
 ![Julia 설치 확인](https://github.com/aasdzs/Jlsca/blob/master/captures/01_check_julia.PNG?raw=true)

2. Jlsca 설치 및 확인
 * Jlsca 소스코드 다운 후 압축풀기
 * Julia 실행하여 다음 명령어 수행 'using Pkg; Pkg.add(PackageSpec(url="https://github.com/Riscure/Jlsca"))'
 ![Jlsca 설치](https://github.com/aasdzs/Jlsca/blob/master/captures/02_install_Jlsca.PNG?raw=true)
 * CMD 창에서 Jlsca 설치 경로로 이동하여 예제 동작 확인
   - Jlsca 설치 경로 예시 (I:\Jlsca-master)
   - 예제 동작 명령어 수행 'julia examples/main-condavg.jl aestraces/aes128_sb_ciph_0fec9ca47fb2f2fd4df14dcb93aa4967.trs'
  ![예제 실행 화면 1](https://github.com/aasdzs/Jlsca/blob/master/captures/03_execute_Jlsca_example-1.PNG?raw=true)
  ![예제 실행 화면 2](https://github.com/aasdzs/Jlsca/blob/master/captures/04_execute_Jlsca_example-2.PNG?raw=true)
   - 현재 다른 예제들은 에러 발생함 (추후 검토 예정)

# Ubuntu 설치 방법

 * 추가 예정
