<img src="assets/banner.svg" width="100%" alt="위건 WI-GEON, Unity Client Developer">

<p>
  <a href="https://velog.io/@w_wgeon">Dev Log</a>
  &nbsp;·&nbsp;
  <a href="mailto:wegeon.dev@gmail.com">Email</a>
</p>

Unity와 C#으로 게임 클라이언트를 만듭니다.<br>
게임 규칙은 엔진으로부터 분리하고, 동작은 테스트하며, 성능은 측정한 수치로 판단합니다.

## Focus

| | |
| :-- | :-- |
| **Architecture** | 어셈블리와 인터페이스로 게임 규칙과 엔진 의존성을 분리합니다. |
| **Reliability** | 결정적 시뮬레이션과 자동화 테스트로 같은 입력의 같은 결과를 보장합니다. |
| **Performance** | 할당과 GC를 직접 측정하고 병목의 근거를 남깁니다. |

## Selected work

### [Todo with Spirits](https://github.com/junsu1023/todo-with-spirits)

할 일을 완료하면 정수가 모이고 정령이 성장하는 게임형 TODO 앱입니다.<br>
4인 팀에서 **Unity 클라이언트 설계와 구현**을 담당하고 있습니다.

<img src="assets/todo-with-spirits.svg" width="680" alt="Todo with Spirits 플레이 화면">

- 게임 규칙을 `noEngineReferences` Core 어셈블리로 분리
- FNV-1a 기반 시드로 결정적 하루 시뮬레이션 구현
- 성장·보상·저장·복원 로직을 **58개 EditMode 테스트**로 검증

[`Core`](https://github.com/junsu1023/todo-with-spirits/tree/develop/unity/TodoSpirits/Assets/TodoSpirits/Scripts/Core)
· [`Tests`](https://github.com/junsu1023/todo-with-spirits/tree/develop/unity/TodoSpirits/Assets/TodoSpirits/Tests)
· [`Commits`](https://github.com/junsu1023/todo-with-spirits/commits/develop/?author=WI-GEON)

### [AllocLab](https://github.com/WI-GEON/system-playground/tree/main/csharp/week01/AllocLab)

Unity에서 GC 스파이크를 만드는 C# 코드 패턴을 직접 측정한 개인 실험입니다.<br>
값/참조 타입, 박싱, 컬렉션, LINQ의 할당과 실행 시간을 같은 조건에서 비교했습니다.

[`Experiments`](https://github.com/WI-GEON/system-playground/tree/main/csharp/week01/AllocLab/Experiments)
· [`Benchmarks`](https://github.com/WI-GEON/system-playground/tree/main/csharp/week01/AllocLab/Benchmarks)
· [`Reports`](https://github.com/WI-GEON/system-playground/tree/main/csharp/week01/AllocLab/Docs)

## Stack

`Unity 6` · `C#` · `Unity Test Framework` · `Rider` · `Visual Studio` · `Git` · `GitHub`

## Contact

[wegeon.dev@gmail.com](mailto:wegeon.dev@gmail.com) · [velog.io/@w_wgeon](https://velog.io/@w_wgeon)

<sub>실무 프로젝트는 계약상 비공개입니다. 상세 포트폴리오는 요청 시 공유드립니다.</sub>
