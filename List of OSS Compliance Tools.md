초안 작성 중 (ETRI 박정숙)
# List of Opensource Compliance tools
## 1) Feactures of each Compliance Tool
| No  | Name of Tool  | License | Descriotion | Website |
| :--: | :--: | :--:  | :--  | :--  | 
| 1 | AboutCode Toolkit | Apache-2.0  | -프로젝트에서 사용하는 외부 SW 구성요소에 대한 원본, 라이선스, 사용 및 기타 정보를 문서화하는 간단한 방법 제공<br />- 고지문을 생성하고 프로젝트에서서 사용되는 재배포 가능한 소스코드 식별 | https://www.aboutcode.org |
| 2 | AboutCode Manager | Apache-2.0  | - 시각적 UI 제공하여 ScanCode로 식별된 라이선스나 기타 알림을 평가하고 구성요소의 유효 라이선스에 대한 결론 기록<br />- Electron  기반, nexB의 AboutCode 도구를 사용하기 위한 기본 데스크톱/GUI 도구  | https://www.aboutcode.org |
| 3 | Apache Rat  | Apache-2.0  | - 라이선스에 중점을 둔 릴리즈 audit 도구 (Apaceh Creadur 프로젝트의 일부)<br />    - Java로 코딩, Maven 및 Ant용 플러그인을 사용하여 명령줄에서 실행 | https://creadur.apache.org/rat |
| 4 | Apache Tentacles  | Apache-2.0 | - 릴리즈할 산출물이 포함된 저장소와의 인터랙션을 자동화하여 검토 작업 단순화 <br /> - Java로 코딩, CLI 실행  | https://creadur.apache.org/tentacles |
| 5 | Apache Whisker  | Apache-2.0  | - 조립된 응용이 올바른 법적 문서를 유지하도록 지원 <br /> - 복잡한 조립 응용 프로그램에 특히 유용 | https://creadur.apache.org/whisker|
| 6 | Bang  | AGPL-3.0  | - 바이너리 파일 분석 도구  <br /> - 바이너리 파일의 내용을 찾아 추출된 정보를 라이선스 준수, 보안 연구 또는 구성 분석과 같은 추가 분석에 사용할 수 있도록 만듦  <br /> - 감지, 압축풀기 및 레이블 지정이 가능한 약 130개의 다양한 파일 형식을 지원 | https://github.com/armijnhemel/binaryanalysis-ng |
| 7 | Barista  | Apache-2.0  | - 오픈소스 구성 요소, 라이선스 및 잠재적인 취약점을 감지하는 스캐닝 도구  <br /> - 다단계 종속성을 포함하여 오픈소스 BOM을 자동으로 생성하고 유지 관리  <br /> - Barista 관리자는 감지된 각 라이선스와 관련된 의무사항을 결정하고 배포 모댈, 적용 가능한 라이선스 및 감지된 종속성에 대한 문서화된 취약성을 기반으로 프로젝트 승인 상태 할당  <br /> - 클라이드 네이티브 아키텍쳐: 필요에 따라 호스팅 유연성과 확장성을 헝용하는 클라우드 네이티브 배포 환경용으로 설계 | https://optum.github.io/barista |
| 8 | Bubby  | MPL-2.0  | - 호환 SW를 안심하고 릴리즈할 수 있도록 지원하는 릴리즈 준비 플랫폼  <br /> - 보고 및 분석을 통해 릴리즈 프로세스에 대한 가시성을 확보하여 위험을 낮추고 품질을 높이며 주기 시간을 단축하고 지속적인 개선 | https://github.com/valocode/bubby |
| 9 | CLA Assistant  | Apache-2.0  | - 기여자가 CLA에 서명할 수 있도록 하여 리포지토리에 대한 기여의 법적인 측면을 처리하는 도구  <br /> - CLA는 GitHub Gist 파일로 저장 후 CLA Assistant의 저장소/조직과 연결 가능 | https://github.com/cla-assistant/cla-assistant |
| 10 | Cregit  | GPL-3.0  | -  소스코드의 기여자 식별 | https://github.com/cregit/cregit |
| 11 | Deltacode  | Apache-2.0  | - 패키지, 구성요소, 코드베이스(제품)의 두 버전에 대한 ScanCode 스캔을 쉽게 비교가능하므로 라이선스 변경사항 식별에 중점을 두고 가능한 변경 사항을 빠르게 식별 가능 <br /> - ScanCode와 함께 DeltaCode를 사용하여 릴리즈 간 오픈소스 타사 SW 패키지, 구성 요소의 라이선스 및 관련 변경사항을 식별/추적 | https://www.aboutcode.org |
| 12 | Eclipse SW360  | EPL-1.0  | - 조직에서 사용하는 SW 구성 요소에 대한 정보 공유를 위한 중앙 저장소를 제공하도록 설계된 SW 카탈로그 응용 프로그램 <br /> - 고유한 작업을 위한 별도의 백엔드 서비스 및 이의 액세스를 위한 포틀릿 제공으로 SW 산출물 및 프로젝트 관리용 인프라에 쉽게 통합 <br /> - 코드 스캔 도구와 같은 외부 시스템과 상호 작용하는 커넥터 제공 | https://projects.eclipse.org/projects/technology.sw360 |
| 13 | Eclipse SW360antenna  | EPL-2.0  | - 오픈소스 라이선스 준수 프로세스를 최대한 자동화하는 도구 <br /> - 1) 모든 규정 준수 관련 데이터 수집 <br /> - 2) 해당 데이터를 처리하고 라이선스 준수 관련 문제가 있을 시 경고 <br /> - 3) 컴플라이언스 산출물 세트 생성(소스코드 번들, 공개 문서, 보고서) | https://projects.eclipse.org/projects/technology.sw360antenna |
| 14 | Fossology  | GPL-2.0  | - 라이선스, 저작권 및 export 통제 스캔을 위한 스캔 도구. SW의 모든 저작권 고지가 포함된 Readme 또는 SPDX 파일 생성 <br /> - 컴플라이언스 워크플로를 위한 웹 UI 및 DB 제공. 스캔 패키지를 서버에 업로드 필요(Monk, Nomos, Ninka) <br /> - 검사된 패키지에 대한 버전 제어가 있으므로 이전 패키지의 최신 버전을 검사할 때 변경된 파일만 다시 검사  | https://www.fossology.org |
| 15 | LDBCollector  | BSD-3-Clause  | - OSS 라이선스 메타데이터를 수집하고 결합하는 응용 프로그램 | https://github.com/maxhbr/LDBcollector |
| 16 | License Compatibility Checker  | MIT  | - SPDX 표준 기반으로 라이선스 호환성을 위한 NPM package.json 종속성 확인 <br /> - 라이선스가 얼마나 허용되는지에 대한 설명 및 패키지의 라이선스를 간단히 비교(허용 > 약한 보호 > 강력한 보호 > 네트워크 보호) | https://github.com/HansHamel/license-compability-checker#readme |
| 17 | Licensee.js  | Apache-2.0  | - 규칙에 대해 NPM 패키지 종속성 라이선스 메타데이터를 확인하는 CLI <br /> - SPDX 라이선스 표현과 화이트리스트 데이터를 사용하여 화이트리스트와 다른 라이선스에 있는 패키지를 캡쳐 | https://github.com/jslicense/licensee.js |
| 18 | Ninka  | GPL-2.0  | - 소스코드용 경량 라이선스 식별 도구 <br /> - 문장 기반이고 소스코드 파일에서 오픈소스 라이선스를 식별하는 간단한 방법 제공 | https://ninka.turingmachine.org |
| 19 | Opossum Tool | Apache-2.0  | - 오픈소스 라이선스 준수를 위해 대규모 코드베이스를 감사하고 인벤토리 하는 경량 앱 <br /> - 다양한 소스의 오픈소스 컴플라이언스 데이터를 관리하고 결합하기 위한 도구 <br /> - 대규모 코드베이스에 대한 규정 준수 정보를 검토하기 위한 경량 앱 <br /> - Opossum.UI: 애플리케이션에 사용되는 오픈소스 소프트웨어 검색, 오픈소스 코드 스캔에서 보고서 생성 | https://github.com/opossum-tool |
| 20 | OSS Attribution Builder  | Apache-2.0  | - SW 제품에 대한 속성 문서를 만드는 데 도움이 되는 웹 사이트 | https://github.com/amzn/oss-attribution-builder |
| 21 | OSS Discovery  |   | -  | https:// |
| 22 | OSS Review Toolkit  |   | -  | https:// |
| 23 | OSSPolice  |   | -  | https:// |
| 24 | Quartermaster Project QMSTR  |   | -  | https:// |
| 25 | ScanCode.io & ScanPipe  |   | -  | https:// |
| 26 | ScanCode Toolkit  |   | -  | https:// |
| 27 | SCANOSS  |   | -  | https:// |
| 28 | SPDX Tools  |   | -  | https:// |
| 29 | SPDX Maven Plugin  |   | -  | https:// |
| 30 | TraceCode Toolkit  |   | -  | https:// |
| 31 | Tern  |   | -  | https:// |
| 32 | Vulnerability Assessment Tool  |   | -  | https:// |
| 33 | REUSE  |   | -  | https:// |
| 34 | FOSSLight  |   | -  | https:// |
| 35 | ClearlyDefined  |   | -  | https:// |
