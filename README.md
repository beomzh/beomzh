<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=2EA6DA&center=true&vCenter=true&width=600&lines=Cloud+Engineer+%40+OpenShift+(OCP);Legacy-to-Cloud+Migration+Specialist;Private+Cloud+%2F+On-Prem+Platform;Always+Building%2C+Always+Learning" alt="Typing SVG" />

<p>
  <img src="https://img.shields.io/badge/Focus-OpenShift%20(OCP)-EE0000?style=flat-square" alt="Focus: OpenShift"/>
  <img src="https://img.shields.io/badge/Focus-Private%20Cloud-2EA6DA?style=flat-square" alt="Focus: Private Cloud"/>
  <img src="https://img.shields.io/badge/Focus-Legacy%20to%20Cloud%20Migration-6A5ACD?style=flat-square" alt="Focus: Legacy to Cloud Migration"/>
</p>

<a href="https://portfolio-wine-mu-83.vercel.app" target="_blank">
  <img src="https://img.shields.io/badge/Portfolio-바로가기-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
</a>

</div>

<br/>

## 소개

**OpenShift Container Platform(OCP)** 을 주력으로 다루는 클라우드 엔지니어입니다.
프라이빗(On-Prem) 클라우드 환경에 강점이 있으며, **레거시 시스템을 컨테이너/클라우드 환경으로 전환**하는 프로젝트를 주로 수행해왔습니다.

- **Legacy → Cloud 전환**: 기존 WAS(JBoss/Tomcat) 기반 레거시 애플리케이션을 OCP 위로 컨테이너화·이관
- **OCP 중심 플랫폼 운영**: OpenShift Container Platform 구축·운영 및 클러스터 설계
- **Private Cloud 강점**: On-Prem/사내 인프라 환경에서의 플랫폼 설계 및 운영 경험
- RKE2 / Rancher / Helm 기반 인프라 자동화


<br/>

## Project Experience

> 공공·금융·통신·에너지 도메인에서 OpenShift(OCP) 기반 프라이빗 클라우드 구축·운영과 레거시→클라우드 전환을 수행했습니다.
> (고객사명은 보안상 도메인으로 표기)

#### 금융권 Private Cloud — OpenShift 재구축 & 블루/그린 마이그레이션

`OpenShift` `RHEL` `Cgroup v2` `Blue-Green Migration`

- 개발 서버 OCP 업그레이드 지원 및 Cgroup v2 마이그레이션 호환성 검증
- 개발 ↔ 운영 서버 간 블루/그린 마이그레이션 설계 및 지원
- 금융권 고가용성 요구 환경에서 무중단 전환 수행

#### Private Cloud 보안 감사 대응 & 결제 서비스 무중단 인증서 교체

`OpenShift Compliance Operator` `grype/syft` `ISMS` `Java Keystore/Truststore`

- 빌드·배포 파이프라인에 컨테이너 이미지 보안 스캔(grype·syft) 단계 추가
- KISA 권고 취약점을 OpenShift Compliance Operator로 점검·조치 (Immutable OS 환경 대응)
- PG 서비스 Java 인증서 교체를 WAS 재기동 절차 단계화로 무중단 수행 → ISMS 감사 대응 완료

#### 공공기관 — 레거시 → 클라우드 네이티브 전환 & 데이터 기반 장애 분석

`Kubernetes` `PaaS` `Apache Benchmark` `Oracle`

- 레거시 시스템의 클라우드 네이티브 전환 전 과정(설계·구축·운영·장애대응) 주도
- ab 테스트로 ALB 타임아웃을 수치로 증명, 네트워크팀과 협업해 해결
- Oracle SQL Plan 갱신 패턴을 규명해 DB 장애 원인 분석에 기여

#### 에너지 공기업 — GPU AI 서비스 인프라 신규 구축

`OpenShift Virtualization` `NVIDIA GPU Operator` `vLLM`

- OpenShift 기반 AI GPU 환경 신규 설계·구축
- NVIDIA GPU Operator로 GPU AI 워크로드 지원 환경 완성
- 생성형 AI 서비스를 위한 컨테이너 기반 GPU 인프라 운영 노하우 확보

#### 대형 통신사 — 대규모 MSA 전환 & 트래픽 폭주 실시간 대응

`Kubernetes` `Istio` `Kiali` `GitLab CI/CD`

- 대규모 MSA 전환에 따른 Kubernetes 기반 컨테이너 환경 설계·구축 참여
- 오픈 직후 과부하 장애 발생 → Kiali 트래픽 맵으로 병목 특정, Istio 가중치 라우팅으로 신속 복구
- 재발 방지책으로 서킷 브레이커(Outlier Detection) 적용 제안 및 대응 절차 문서화

<details>
<summary><b>기타 프로젝트 더보기</b></summary>
<br/>

| 프로젝트 | 도메인 | 핵심 기술 |
|---|---|---|
| OpenShift 무중단 업그레이드 / 클러스터 증설 | 공공 | OpenShift |
| 통합 로그 · CI/CD 전사 자동화 구축 | 사내/공통 | Fluent Bit, ELK/EFK, Loki, GitLab, Harbor, Jenkins, Nexus |
| APM · 세션 클러스터링 구축 지원 & WAS 튜닝 | 공통 | Tomcat, APM, GC 로그 분석 |
| AI Kubernetes 플랫폼 구축 (모델 서빙) | 공공 (2건) | RKE2, vLLM, GPT-OSS / Gemma / BGE-M3 |
| JBoss 6 → 8 마이그레이션 | 금융 | Red Hat MTA, JBoss(WildFly) |
| 자사 솔루션 구축 — 레거시 OS 제약 극복 | 금융 | RHEL, Docker |
| OS 구축 및 PaaS 안정화 | 공공 | RHEL, PaaS |
| WEB/WAS 이중화 구성 | 공공 | Apache HTTPD, Tomcat |
| 레거시 시스템 분석 & Kubernetes 마이그레이션 | 교육 | Kubernetes |
| 퍼블릭 클라우드 운영 | 통신 | AWS (EKS, EC2, ALB) |

</details>

<br/>

## Tech Stack

**Container & Orchestration** _(★ OpenShift 주력)_

<p>
  <img src="https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white" alt="OpenShift"/>
  <img src="https://img.shields.io/badge/OpenShift_Virtualization-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white" alt="OpenShift Virtualization"/>
  <img src="https://img.shields.io/badge/RKE2-0075A8?style=for-the-badge&logo=rancher&logoColor=white" alt="RKE2"/>
  <img src="https://img.shields.io/badge/Rancher-0075A8?style=for-the-badge&logo=rancher&logoColor=white" alt="Rancher"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm"/>
</p>

**Middleware / WAS**

<p>
  <img src="https://img.shields.io/badge/JBoss-EC7A08?style=for-the-badge&logo=redhat&logoColor=white" alt="JBoss"/>
  <img src="https://img.shields.io/badge/Apache_HTTPD-D22128?style=for-the-badge&logo=apache&logoColor=white" alt="Apache HTTPD"/>
  <img src="https://img.shields.io/badge/Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black" alt="Tomcat"/>
</p>

**Cloud**

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud"/>
</p>

**Automation / IaC**

<p>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible"/>
</p>

**Auth / Identity**

<p>
  <img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white" alt="Keycloak"/>
  <img src="https://img.shields.io/badge/Google_OIDC-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google OIDC"/>
  <img src="https://img.shields.io/badge/OAuth2--Proxy-000000?style=for-the-badge" alt="OAuth2 Proxy"/>
</p>

<br/>

## Certifications

<p>
  <img src="https://img.shields.io/badge/CKA-Certified_Kubernetes_Administrator-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="CKA"/>
</p>

- **CKA** (Certified Kubernetes Administrator) — Linux Foundation, 2024.03
- **무선설비기사** — 한국방송통신전파진흥원, 2022.09

<br/>

## GitHub Stats

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=beomzh&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
<img src="https://github-stats-extended.vercel.app/api/top-langs?username=beomzh&layout=compact&theme=tokyonight&hide_border=true" alt="Top Langs" height="165"/>

<img src="https://streak-stats.demolab.com/?user=beomzh&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>

</div>

<br/>

## Contact

<p>
  <a href="https://portfolio-wine-mu-83.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="mailto:kimjm3435@gmail.com">
    <img src="https://img.shields.io/badge/Email-kimjm3435%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://beom0288.tistory.com/" target="_blank">
    <img src="https://img.shields.io/badge/Blog-Tistory-FF5722?style=for-the-badge&logo=rss&logoColor=white" alt="Tistory Blog"/>
  </a>
</p>

<br/>

<div align="center">
<img src="https://komarev.com/ghpvc/?username=beomzh&style=for-the-badge&color=2EA6DA" alt="Profile Views"/>
</div>
