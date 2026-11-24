# Security Engineering

웹·인프라 모의해킹을 중심으로 공부하고 있습니다. 웹 서비스와 시스템의 구조를 이해하고, 취약점이 어떤 공격 경로로 이어지는지 분석하는 데 관심이 있습니다.

## About Me

정보보안공학을 전공하며 웹·시스템 보안, 네트워크, 보안 프로젝트를 중심으로 학습하고 있습니다. 장기적으로 클라우드 보안과 레드팀 분야로 관심을 넓혀가는 것이 목표입니다.

## Areas of Interest

- **Web Security** — 웹 애플리케이션 구조와 취약점 분석
- **Infrastructure & System Security** — Linux 환경, 시스템 구조 및 권한
- **Attack Path Analysis** — 취약점 간 연결과 공격 경로 분석
- **Cloud Security** — 컨테이너와 Kubernetes 보안에 대한 관심

## Project Tech Stack

| Project | Technologies |
| --- | --- |
| CTF-OS | Python, Linux / WSL2, Docker, uv, Codex CLI |
| MCP Capstone | Python, Docker, uv, pytest |

*프로젝트 문서와 설정에 기재된 환경이며, 개인의 숙련도를 나타내는 목록은 아닙니다.*

## Featured Projects

### [CTF-OS](https://github.com/whatevertakes/CTF-OS) | WT 조직 프로젝트

CTF 문제의 실행·관리와 분석을 지원하는 Python 기반 프로젝트입니다.

- **구성:** CLI 기반 문제 관리 및 실행 흐름
- **실행 방식:** Managed / Assisted
- **환경:** Linux / WSL2, 문제별 Docker sandbox

### MCP Tool Composition Security | 팀 연구 · 진행 중

다중 MCP 도구의 조합에서 발생할 수 있는 위험 경로를 분석하고 실행 통제를 평가하는 캡스톤 연구입니다. 연구 완료 후 공개 가능한 결과와 저장소를 연결할 예정입니다.

### WhiteHat School Kubernetes Security Project | 팀 프로젝트

WhiteHat School에서 진행한 교육용 Kubernetes 보안 실습 팀 프로젝트입니다. 팀원들과 4개 보안 시나리오 후보를 조사하고 선정 기준을 정리했으며, 시나리오 1의 설계·개발·검증과 문서화에 참여했습니다.

- **My contribution:**
  - 4개 보안 시나리오 후보 조사 및 선정 기준 정리
  - 시나리오 1의 ServiceAccount / RBAC 보안 문제 설계 참여
  - 실습용 취약 웹 애플리케이션 개발 참여
  - 시나리오 실행·검증 및 보고서·발표 자료 작성 참여
  - 다른 시나리오의 검증과 문서화 협업
- **Team scope:** 교육용 Kubernetes 보안 시나리오 설계와 팀 협업 기반 실습 결과 정리
- **Team note:** 최종 결과물은 여러 팀원의 공동 작업으로 완성되었으며, 위 내용은 확인된 개인 참여 범위만 설명합니다.

## Security Activities

### Personal Kubernetes Infrastructure Practice

개인 Minikube 및 VMware 기반 환경에서 Kubernetes 멀티노드 클러스터를 구성하고, Control Plane과 Worker Node의 기본 상태를 확인했습니다.

- 개인 환경에서 containerd, kubeadm, Calico를 사용한 클러스터 구성
- Node `Ready` 및 주요 시스템 Pod `Running` 상태 확인

## Awards and Honors

- **2026 KISIA 정보보호 경진대회** — 2026년 8월 본선 참가
  - [참가 확인서 보기](assets/certificates/kisia-2026.png)

## Security Learning

- **Kubernetes / Minikube / RBAC** — 개인 환경에서 기본 Workload와 ServiceAccount, Role, RoleBinding을 구성하고 상태와 권한 확인 흐름을 실습했습니다.
- **VMware Multi-node Kubernetes** — VMware 기반 멀티노드 클러스터를 구성하고 containerd, kubeadm, Calico 적용 및 Node·시스템 Pod 상태를 검증했습니다.
- **Helm** — 개인 클러스터에서 Release 설치, replica 변경 Upgrade, Revision 확인 및 Rollback 흐름을 확인했습니다.
- **Argo CD** — Argo CD를 설치하고 공개 예제 Application의 Manual Sync 및 재동기화 후 상태 복구 흐름을 확인했습니다.
