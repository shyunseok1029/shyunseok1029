# 박현석 (Hyunseok Park)

상명대학교 정보보안공학과 학부생이며, 웹, 인프라 모의해킹을 중심으로 공부하고 있습니다. 장기적으로 클라우드 보안과 레드팀 분야로 취업을 준비하고 있습니다

## Areas of Interest

- **Web Security** — 웹 애플리케이션 구조와 취약점 분석
- **Attack Path Analysis** — 취약점 간 연결과 공격 경로 분석
- **Cloud Security** — 컨테이너와 Kubernetes 보안에 대한 관심

## Featured Projects

### [CTF-OS](https://github.com/whatevertakes/CTF-OS) | WT 조직 프로젝트

CTF 문제의 실행·관리와 분석을 지원하는 Python 기반 프로젝트입니다.

- **기술 환경:** Python, Linux / WSL2, Docker, uv, Codex CLI
- **구성:** CLI 기반 문제 관리 및 실행 흐름
- **실행 방식:** Managed / Assisted
- **환경:** Linux / WSL2, 문제별 Docker sandbox

### MCP Tool Composition Security | 팀 연구 · 진행 중

다중 MCP 도구의 조합에서 발생할 수 있는 위험 경로를 분석하고 실행 통제를 평가하는 캡스톤 연구입니다.

- **기술 환경:** Python, Docker, uv, pytest
- **연구 목적:** 다중 MCP 도구 조합에서의 위험 경로 분석 및 실행 통제 평가
- **상태:** 연구 완료 후 공개 가능한 결과와 GitHub 저장소를 연결할 예정입니다.

### WhiteHat School Kubernetes Security Project | 팀 프로젝트

WhiteHat School에서 진행한 교육용 Kubernetes 보안 팀 프로젝트입니다. 팀원들과 4개 보안 시나리오 후보를 조사하고 선정 기준을 정리했으며, 시나리오 1의 설계·개발·검증과 문서화에 참여했습니다.

- **기술 환경:** Kubernetes, ServiceAccount, RBAC, 실습용 웹 애플리케이션
- **주요 범위:** 교육용 보안 시나리오 설계, 실습 환경 준비, 시나리오 실행·검증 및 결과 문서화
- **My contribution:**
  - 4개 보안 시나리오 후보 조사 및 선정 기준 정리
  - 시나리오 1의 ServiceAccount / RBAC 보안 문제 설계 참여
  - 실습용 취약 웹 애플리케이션 개발 참여
  - 시나리오 실행·검증 및 보고서·발표 자료 작성 참여
  - 다른 시나리오의 검증과 문서화 협업
- **Team note:** 최종 결과물은 여러 팀원의 공동 작업으로 완성되었으며, 위 내용은 확인된 개인 기여 범위만 설명합니다.

## Security Activities & Learning

### Personal Kubernetes Infrastructure Practice

개인 Minikube 및 VMware 기반 환경에서 Kubernetes 멀티노드 클러스터를 구성하고, Control Plane과 Worker Node의 기본 상태를 확인했습니다.

- 개인 환경에서 containerd, kubeadm, Calico를 사용한 클러스터 구성
- Node `Ready` 및 주요 시스템 Pod `Running` 상태 확인
- **Kubernetes / Minikube / RBAC:** 기본 Workload와 ServiceAccount, Role, RoleBinding을 구성하고 상태와 권한 확인 흐름을 실습
- **VMware Multi-node Kubernetes:** VMware 기반 멀티노드 클러스터 구성과 containerd, kubeadm, Calico 적용 및 Node·시스템 Pod 상태 검증
- **Helm:** 개인 클러스터에서 Release 설치, replica 변경 Upgrade, Revision 확인 및 Rollback 흐름 확인
- **Argo CD:** Argo CD 설치, 공개 예제 Application의 Manual Sync, 재동기화 및 상태 복구 흐름 확인

### Other Learning Areas

- **Web Security** — HTTP 및 웹 애플리케이션 보안
- **Network Security** — TCP/IP 및 네트워크 보안
- **System Security** — Linux, 프로세스 및 권한 관리
- **Cloud Security** — Docker 및 Kubernetes 보안 학습

## Awards and Honors

- **2026 KISIA 정보보호 경진대회** — 2026년 8월 본선 참가
  - [참가 확인서 보기](assets/certificates/kisia-2026.png)
