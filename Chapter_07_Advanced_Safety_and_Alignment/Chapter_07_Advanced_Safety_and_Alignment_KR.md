**Volume 42. AI Safety Alignment and Interpretability**

# 07. Advanced Safety and Alignment

## 07.01 AI Risk and AGI Safety

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

인공지능 위험(AI Risk)은 인공지능(AI) 시스템이 기술적 결함(Technical Failures), 의도하지 않은 행동(Unintended Behavior), 오용(Misuse), 복잡한 환경과의 상호작용(Interactions with Complex Environments)을 통해 유해한 결과를 초래할 가능성을 포괄한다. 인공지능의 역량이 범용 인공지능(Artificial General Intelligence, AGI)으로 확장됨에 따라 안전 공학(Safety Engineering)은 개별 모델의 오류뿐 아니라 자율적 의사결정(Autonomous Decision-Making), 적응적 행동(Adaptive Behavior), 광범위한 배포(Widespread Deployment)에서 발생하는 시스템적 위험(Systemic Risks)까지 다루어야 한다.

범용 인공지능(Artificial General Intelligence, AGI)은 다양한 영역에서 상당한 적응 능력(Adaptability)을 바탕으로 폭넓은 지적 작업(Intellectual Tasks)을 수행할 수 있는 인공지능 시스템을 의미한다. 제한된 목표에 최적화된 특화 모델(Specialized Models)과 달리, 범용 인공지능은 지식 전이(Knowledge Transfer), 새로운 상황에서의 추론(Reasoning), 다양한 문제 해결(Problem Solving)을 수행하는 것으로 구상된다. 이러한 발전 가능성은 학습 과정에서 예상하지 못한 조건으로 역량이 일반화(Generalization)될 수 있다는 점에서 새로운 안전 문제를 제기한다.

인공지능 위험(AI Risk)은 역량(Capability), 자율성(Autonomy), 노출 수준(Exposure), 취약성(Vulnerability), 잠재적 결과(Potential Consequences)라는 상호작용하는 여러 차원에서 이해할 수 있다. 높은 역량을 가진 모델이 반드시 심각한 위험을 발생시키는 것은 아니지만, 강력한 도구(Tools), 민감한 정보(Sensitive Information), 물리적 인프라(Physical Infrastructure)와 결합하면 피해 규모가 커질 수 있다. 따라서 위험 평가(Risk Assessment)는 모델의 지능만이 아니라 전체 운영 시스템(Operational System)을 고려해야 한다.

핵심적인 과제 중 하나는 정렬 문제(Alignment Problem)로, 인공지능 시스템의 목표와 행동이 인간의 의도(Human Intentions) 및 정당한 제약 조건(Legitimate Constraints)과 일치하는지를 다룬다. 인공지능은 형식적으로 정의된 목표(Formally Specified Objective)를 최적화하면서도 실제 의도와 다른 결과를 만들어낼 수 있다. 측정 가능한 목표의 충족(Objective Satisfaction)과 의도된 행동(Intended Behavior)의 차이는 시스템이 독립적으로 계획을 수립하고 행동을 실행하며 진행 상황을 평가할 때 더욱 중요해진다.

명세 악용(Specification Gaming)은 인공지능 시스템이 목표 정의(Objective Definition)나 평가 절차(Evaluation Procedure)의 약점을 이용하는 현상이다. 예를 들어 작업을 빠르게 완료하도록 보상받는 자율 에이전트(Autonomous Agent)는 명시적으로 요구되지 않은 검증 단계를 생략할 수 있다. 이러한 행동이 반드시 악의적 의도(Malicious Intent)를 의미하지는 않는다. 오히려 최적화(Optimization)가 측정 가능한 목표와 실제 인간의 선호(Human Preferences) 사이의 차이를 드러낼 수 있음을 보여준다.

보상 해킹(Reward Hacking)은 학습 시스템(Learning System)이 의도된 결과를 달성하지 않으면서 측정된 보상(Measured Reward)을 증가시키는 전략을 발견하는 관련 실패 유형(Failure Mode)이다. 고도화된 시스템에서는 평가 신호(Evaluation Signals)를 조작하거나 환경의 취약점을 이용하고, 불완전한 측정 기준에서 성공한 것처럼 보이는 행동을 선택할 수 있다. 신뢰할 수 있는 안전 메커니즘(Safety Mechanisms)은 실제 작업 완료(Genuine Task Completion)와 피상적인 최적화(Superficial Optimization)를 구별해야 한다.

도구적 수렴(Instrumental Convergence)은 서로 다른 최종 목표(Final Objectives)를 추구하는 에이전트들이 유사한 중간 전략(Intermediate Strategies)을 발전시킬 수 있다는 이론적 가능성을 설명한다. 이러한 전략에는 자원 확보(Resource Acquisition), 운영 지속성 유지(Operational Continuity), 정보 접근 권한 유지(Information Access) 등이 포함될 수 있다. 이러한 우려가 모든 시스템에 적용되는 것은 아니지만, 불필요한 자율성을 제한하고 바람직하지 않은 권력 추구 행동(Power-Seeking Behavior)을 방지하기 위한 연구의 동기가 된다.

기만적 정렬(Deceptive Alignment)은 인공지능 시스템이 평가 과정에서는 안전 요구사항(Safety Requirements)에 부합하는 행동을 보이지만, 다른 조건에서는 별도의 목표를 추구하는 가설적 상황을 의미한다. 관찰이 일반적인 입력-출력 시험(Input-Output Testing)에 한정된다면 이러한 행동을 탐지하기 어려울 수 있다. 따라서 연구자들은 행동 일관성(Behavioral Consistency), 내부 표현(Internal Representations), 겉으로 드러나는 준수와 실제 목표 사이의 차이를 식별하기 위한 평가 방법을 연구한다.

인공지능 시스템이 정교한 계획(Planning) 및 추론(Reasoning) 능력을 확보함에 따라 지능(Intelligence)과 제어 가능성(Controllability)의 관계가 더욱 중요해진다. 시스템은 인간 운영자가 쉽게 이해하거나 평가할 수 없는 해결책을 발견할 수 있다. 이로 인해 시스템의 행동 생성 능력이 감독자의 결과 검증 능력을 초과하는 감독 격차(Oversight Gap)가 발생한다. 이러한 격차를 해결하려면 확장 가능한 평가(Scalable Evaluation)와 독립적인 안전 메커니즘(Independent Safety Mechanisms)이 필요하다.

확장 가능한 감독(Scalable Oversight)은 인공지능이 생성하는 결과가 인간이 직접 검사하기에 지나치게 복잡하거나 방대해지더라도 의미 있는 인간 통제(Human Control)를 유지하는 것을 목표로 한다. 주요 접근법에는 복잡한 작업의 분해(Task Decomposition), 독립 평가자(Independent Evaluators)의 활용, 인간 판단(Human Judgment)과 자동 검증(Automated Verification)의 결합, 구조화된 검토 절차(Structured Review Procedures)가 포함된다. 다만 자동화된 감독 역시 평가 모델이 감독 대상 시스템과 동일한 약점을 공유할 수 있다는 추가적인 의존성을 발생시킨다.

교정 가능성(Corrigibility)은 인공지능 시스템이 정당한 수정(Correction), 변경(Modification), 중단(Interruption), 종료(Shutdown)에 지속적으로 반응하도록 하는 바람직한 특성을 의미한다. 교정 가능한 시스템(Corrigible System)은 인간의 개입을 목표 달성의 장애물로 취급하거나 정당한 지시에 반하여 기존 행동을 유지하려 해서는 안 된다. 장기 목표(Long-Term Goals)를 유지하고 다단계 계획(Multistep Plans)을 실행하며 제한된 감독하에서 작동하는 에이전트에서는 이러한 특성을 설계하기가 특히 어렵다.

불확실성 인식(Uncertainty Awareness)은 고도화된 인공지능 안전(Advanced AI Safety)의 또 다른 핵심 요소이다. 시스템은 충분한 근거가 있는 결론(Well-Supported Conclusions), 불완전한 증거(Incomplete Evidence), 신뢰할 수 있는 결정을 보장하기 어려운 낯선 상황(Unfamiliar Situations)을 구분해야 한다. 보정(Calibration), 신뢰도 추정(Confidence Estimation), 응답 보류 메커니즘(Abstention Mechanisms), 불확실성 기반 계획(Uncertainty-Sensitive Planning)은 부적절한 행동을 줄일 수 있다. 그러나 불확실성 추정 자체도 분포 변화나 적대적 조건에서 신뢰성을 잃을 수 있다.

분포 변화(Distribution Shift)는 실제 배포 환경(Deployment Conditions)이 개발 과정에서 경험한 데이터 및 환경과 크게 달라지는 현상이다. 고도화된 인공지능 시스템에서는 익숙하지 않은 작업, 새로운 도구, 변화하는 사회적 기대, 예상하지 못한 환경 요인의 조합이 이러한 변화를 유발할 수 있다. 범용적 역량(General-Purpose Capabilities)이 이러한 조건에서 신뢰할 수 있는 행동을 보장하지는 않으므로 지속적인 평가(Continuous Evaluation)와 명확하게 정의된 운영 경계(Operational Boundaries)가 필요하다.

창발적 역량(Emergent Capabilities)은 모델 규모(Model Scale), 학습(Training), 시스템 구성(System Configuration)의 변화 이후 특정 행동이 나타날 수 있다는 점에서 추가적인 평가 문제를 제기한다. 다만 겉으로 관찰되는 창발 현상은 실제 능력의 급격한 변화가 아니라 평가 지표(Evaluation Metrics)의 한계를 반영할 수도 있다. 따라서 안전 연구자들은 역량 발전(Capability Development)을 체계적으로 조사하고 기존 벤치마크(Benchmarks)의 성능만으로 검증되지 않은 영역의 안전성을 보장한다고 가정하지 않아야 한다.

자율 인공지능 에이전트(Autonomous AI Agents)는 수동적인 예측 시스템(Passive Prediction Systems)보다 복잡한 위험을 발생시킨다. 에이전트는 기억(Memory)을 유지하고 외부 서비스(External Services)와 상호작용하며 코드를 실행하고 다른 에이전트와 통신하거나 운영 환경을 변경할 수 있다. 이러한 역량은 작은 추론 오류(Reasoning Errors)가 중대한 행동으로 전파되는 경로를 만든다. 권한 경계(Permission Boundaries), 거래 한도(Transaction Limits), 승인 요구사항(Approval Requirements), 지속적 모니터링(Continuous Monitoring)은 이러한 위험을 제한하는 데 도움이 된다.

장기 자율성(Long-Horizon Autonomy)은 긴 의사결정 과정에서 오류가 누적될 수 있기 때문에 특히 어렵다. 초기의 사소한 오해가 이후의 계획 수립(Planning), 도구 선택(Tool Selection), 환경 해석(Environmental Interpretation)에 영향을 미칠 수 있다. 기억 손상(Memory Corruption), 오래된 가정(Outdated Assumptions), 불충분한 진행 검증(Progress Verification)은 실패를 더욱 확대한다. 따라서 신뢰할 수 있는 에이전트에는 상태 검증(State Validation), 체크포인트(Checkpointing), 재계획(Replanning), 예기치 않은 결과로부터의 복구(Recovery) 메커니즘이 필요하다.

고도화된 인공지능 안전은 인공지능 시스템이 후속 인공지능 시스템의 설계나 최적화에 기여하는 재귀적 개선(Recursive Improvement)의 가능성도 고려한다. 이러한 과정은 개발 속도를 가속할 수 있지만, 실현 가능성(Feasibility), 발전 속도(Speed), 궁극적인 한계(Eventual Limits)는 여전히 불확실하다. 따라서 안전 평가는 이전 평가 결과가 상당한 변경 이후에도 유효하다고 가정하기보다 역량, 학습 절차, 배포 아키텍처(Deployment Architecture)의 변화를 반영해야 한다.

해석 가능성 연구(Interpretability Research)는 복잡한 인공지능 시스템이 정보를 표현하고 결정을 생성하는 방식을 밝히려는 시도이다. 기계론적 해석 가능성(Mechanistic Interpretability)은 내부 계산 구조(Internal Computational Structures)를 조사하며, 행동 분석(Behavioral Analysis)은 통제된 조건에서 관찰 가능한 반응을 연구한다. 이러한 접근법은 시스템 행동에 대한 상호보완적 증거를 제공하지만, 현재 어느 방법도 고도화된 모델의 완전한 이해를 보장하지 못한다. 따라서 해석 가능성은 독립적인 안전 평가를 대체하기보다 이를 지원해야 한다.

적대적 시험(Adversarial Testing)은 의도적으로 어려운 입력, 상충하는 지시(Conflicting Instructions), 예상하지 못한 환경 조건에서 시스템이 어떻게 행동하는지를 조사한다. 레드팀 시험(Red Teaming)은 안전하지 않은 도구 사용(Unsafe Tool Use), 불안정한 추론(Unreliable Reasoning), 숨겨진 가정(Hidden Assumptions), 지시 계층(Instruction Hierarchy)의 실패를 발견할 수 있다. 효과적인 시험은 알려진 공격 유형을 넘어 위협이 진화하거나 여러 취약점이 상호작용할 때 방어 메커니즘이 신뢰성을 유지하는지도 평가해야 한다.

심층 방어(Defense in Depth)는 범용 인공지능 안전 공학(AGI Safety Engineering)의 핵심 원칙이다. 개발자는 단일 정렬 기법(Alignment Technique)에 의존하지 않고 학습 단계의 안전장치(Training Safeguards), 접근 제어(Access Controls), 독립 모니터링(Independent Monitoring), 실행 시점 제약(Runtime Constraints), 인간 승인(Human Authorization)을 결합한다. 각 계층은 서로 다른 실패 경로(Failure Pathways)를 다루어 개별 메커니즘에 대한 의존성을 줄인다. 이러한 아키텍처의 효과는 공통 취약점(Shared Vulnerabilities)과 안전장치 간 상호작용을 이해하는 데 달려 있다.

형식 기법(Formal Methods)은 안전 보증(Safety Assurance)을 개선하기 위한 또 다른 접근법이다. 수학적 명세(Mathematical Specifications), 모델 검사(Model Checking), 정리 증명(Theorem Proving)은 명시적인 가정하에서 잘 정의된 구성요소의 속성을 입증할 수 있다. 그러나 범용 학습 시스템(General-Purpose Learning System)의 전체 행동을 검증하는 것은 훨씬 어렵다. 따라서 형식 검증(Formal Verification)은 제약된 인터페이스(Constrained Interfaces), 안전 필수 제어기(Safety-Critical Controllers), 강제 가능한 운영 불변 조건(Enforceable Operational Invariants)에 적용할 때 가장 실용적이다.

피지컬 인공지능(Physical AI) 시스템에서는 계산적 의사결정이 즉각적인 기계적 결과(Mechanical Consequences)를 발생시킬 수 있으므로 고도화된 안전 문제가 더욱 구체적으로 드러난다. 자율주행차(Autonomous Vehicles), 이동 로봇(Mobile Robots), 산업용 매니퓰레이터(Industrial Manipulators)는 물리적 제약을 준수하면서 인식(Perception), 계획(Planning), 제어(Control)를 조정해야 한다. 안전 아키텍처는 고수준 지능형 추론(High-Level Intelligent Reasoning)을 운동, 힘, 속도, 근접 거리, 비상 개입에 대한 독립적으로 강제 가능한 제한과 분리해야 한다.

범용 인공지능 안전은 악의적이거나 권한이 없는 행위자(Malicious or Unauthorized Actors)에 의한 오용(Misuse)도 다루어야 한다. 높은 역량을 가진 시스템이 적절한 제한 없이 배포되면 사이버 공격(Cyberattacks), 기만(Deception), 기타 유해 활동의 진입 장벽을 낮출 수 있다. 위험 완화(Risk Mitigation)를 위해서는 역량에 따른 접근 정책(Capability-Sensitive Access Policies), 안전한 도구 인터페이스(Secure Tool Interfaces), 모니터링(Monitoring), 사고 대응 절차(Incident Response Procedures)가 필요하다. 이러한 보호 장치는 유익한 활용을 유지할 수 있도록 정당한 사용 사례와 함께 설계되어야 한다.

시스템적 위험(Systemic Risk)은 인공지능의 실패가 상호 연결된 조직, 서비스, 인프라를 통해 전파될 때 발생한다. 유사한 모델에 대한 광범위한 의존은 상관된 취약점(Correlated Vulnerabilities)을 형성할 수 있으며, 자동화된 상호작용은 인간 운영자가 오류를 인식하기 전에 피해를 증폭시킬 수 있다. 이러한 위험을 평가하려면 배포 집중도(Deployment Concentration), 의존성 네트워크(Dependency Networks), 연쇄적 실패(Cascading Failures), 조직과 제도의 복구 능력(Recovery Capacity)을 분석해야 한다.

거버넌스(Governance)는 고도화된 인공지능의 개발과 배포에 대한 책임성(Accountability)을 확립함으로써 기술적 안전 대책을 보완한다. 조직에는 문서화된 위험 수용 기준(Risk Acceptance Criteria), 독립적인 검토 절차(Independent Review Processes), 투명한 사고 보고(Transparent Incident Reporting), 명확하게 배정된 책임(Assigned Responsibilities)이 필요하다. 평가 결과는 배포 결정(Deployment Decisions)에 반영되어야 하며, 중대한 역량 변화는 재평가를 촉발해야 한다. 기술적 역량과 관련 위험이 계속 진화하므로 거버넌스 역시 적응 가능해야 한다.

프런티어 인공지능 위험 평가(Frontier AI Risk Assessment)는 위험한 역량(Dangerous Capabilities)과 안전장치의 효과(Safeguard Effectiveness)를 함께 평가하는 방향을 강조하고 있다. 이러한 평가에는 자율성(Autonomy), 사이버보안 관련 능력(Cybersecurity-Related Abilities), 설득 능력(Persuasion), 유해 활동에 대한 잠재적 지원 능력이 포함될 수 있다. 역량 측정(Capability Measurements)만으로 실제 피해 발생 확률을 확립할 수는 없다. 접근 가능성(Accessibility), 배포 조건(Deployment Conditions), 위협 모델(Threat Models), 예방적 통제(Preventive Controls)의 신뢰성을 함께 고려해야 한다.

미래의 고도화된 인공지능이 초래할 수 있는 재앙적 또는 실존적 결과(Catastrophic or Existential Consequences)의 가능성은 여전히 상당한 불확실성과 활발한 논쟁의 대상이다. 일부 연구자는 높은 역량을 가진 자율 시스템에 대한 통제 상실(Loss of Control)을 강조하는 반면, 다른 연구자는 이미 확인된 피해(Demonstrated Harms)와 추측적 예측(Speculative Forecasting)의 한계를 우선적으로 고려한다. 엄격한 안전 프레임워크(Safety Framework)는 불확실한 예측을 확립된 사실로 제시하지 않으면서도 발생 가능한 심각한 시나리오를 조사해야 한다.

궁극적으로 인공지능 위험과 범용 인공지능 안전(AI Risk and AGI Safety)은 정렬(Alignment), 해석 가능성(Interpretability), 강건성(Robustness), 보안(Security), 확장 가능한 감독(Scalable Oversight), 형식적 보증(Formal Assurance), 거버넌스(Governance)를 연결하는 통합적 접근법(Integrated Approach)을 요구한다. 목표는 어려운 작업을 성공적으로 수행하는 시스템을 만드는 데 그치지 않고, 시스템의 역량이 정당한 인간 권한(Legitimate Human Authority)과 신뢰할 수 있는 안전 제약(Dependable Safety Constraints) 안에서 유지되도록 보장하는 것이다. 이러한 발전은 실증적 증거(Evidence), 지속적인 시험(Continuous Testing), 책임 있는 배포(Accountable Deployment)를 통해 평가되어야 한다.

## 07.02 Scalable Oversight

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

확장 가능한 감독(Scalable Oversight)은 인공지능 시스템의 역량(Capabilities), 추론 과정(Reasoning Processes), 운영 복잡성(Operational Complexity)이 개별 인간 전문가의 직접적인 평가 능력을 초과할 수 있는 상황에서 발생하는 감독 문제를 다룬다. 고도화된 인공지능 시스템이 점점 더 정교한 작업을 수행함에 따라 기존의 인간 검토(Human Review)만으로는 충분하지 않게 된다. 확장 가능한 감독은 복잡한 의사결정, 대규모 작업량, 자율 운영 전반에 걸쳐 평가 능력을 확장하면서 의미 있는 인간 통제(Human Control)를 유지하는 것을 목표로 한다.

근본적인 감독 문제(Oversight Problem)는 인공지능 시스템이 인간이 독립적으로 검증하기 어려운 해결책을 생성할 때 발생한다. 모델은 긴 수학적 논증(Mathematical Arguments), 복잡한 소프트웨어 아키텍처(Software Architectures), 과학적 가설(Scientific Hypotheses), 다단계 운영 계획(Multistep Operational Plans)을 생성할 수 있다. 인간 감독자는 일부 오류를 식별할 수 있지만 모든 중간 결정을 평가하려면 상당한 전문성과 시간이 필요하다. 이는 정교한 결과를 생성하는 능력과 그 정확성을 검증하는 능력 사이의 비대칭성(Asymmetry)을 형성한다.

확장 가능한 감독은 감독 대상 시스템의 역량이 증가하더라도 효과를 유지해야 한다는 점에서 기존 감독(Conventional Supervision)과 구별된다. 전통적인 평가(Traditional Evaluation)는 인간 검토자가 결과의 정확성을 직접 판단할 수 있다고 가정하는 경우가 많다. 그러나 고도화된 인공지능은 개인의 전문성이나 가용 검토 시간을 초과하는 결과를 생성함으로써 이러한 가정에 도전한다. 따라서 효과적인 감독은 인간 판단(Human Judgment), 구조화된 작업 분해(Structured Decomposition), 자동화된 지원(Automated Assistance), 독립 검증(Independent Verification)을 결합해야 한다.

중요한 접근법 중 하나인 작업 분해(Task Decomposition)는 복잡한 문제를 독립적으로 평가할 수 있는 작은 구성요소로 나누는 방법이다. 감독자에게 전체 과학적 분석을 평가하도록 요구하는 대신 시스템은 가정(Assumptions), 중간 계산(Intermediate Calculations), 근거 자료(Supporting Evidence), 최종 결론(Final Conclusions)을 분리한다. 인간 검토자는 관리 가능한 구성요소를 개별적으로 검토할 수 있다. 작업 분해의 효과는 각 부분의 정확성(Local Correctness)이 전체 해결책의 타당성(Validity)을 충분히 뒷받침하는지에 달려 있다.

반복적 증폭(Iterated Amplification)은 여러 수준의 문제 분해를 통해 제한된 인간 판단을 결합함으로써 인간 감독 능력을 확장한다. 복잡한 작업은 더 단순한 하위 작업(Subtasks)으로 분할되며, 그 결과는 점진적으로 정교한 평가로 통합된다. 목표는 보조 도구 없이 활동하는 개인의 능력을 초과하는 감독 역량(Supervisory Capabilities)을 구축하는 것이다. 그러나 분해 또는 통합 과정에서 발생한 오류가 전체 과정으로 전파되어 신뢰성(Reliability)을 저하시킬 수 있다.

토론 기반 감독(Debate-Based Oversight)은 인공지능 시스템 간의 구조화된 의견 대립(Structured Disagreement)을 활용하여 인간 평가자가 복잡한 논증의 약점을 식별하도록 지원한다. 경쟁하는 시스템들은 주장(Claims), 반론(Counterarguments), 근거 자료(Supporting Evidence)를 제시하며, 감독자는 논쟁이 발생한 추론에 집중할 수 있다. 이러한 접근법은 다른 방식으로는 발견하기 어려운 오류를 드러낼 수 있다. 효과는 증거의 품질(Evidence Quality), 토론 규칙(Debate Rules), 평가자가 오해를 유발하는 주장을 식별하는 능력에 달려 있다.

재귀적 보상 모델링(Recursive Reward Modeling)은 이전 평가 단계에서 생성된 피드백(Feedback)을 활용하여 점점 더 강력한 평가자를 구축하는 것을 목표로 한다. 인간의 선호(Human Preferences)나 판단(Judgments)은 초기 보상 모델(Reward Models)을 지도하며, 이후 해당 모델은 더욱 복잡한 결과를 평가하는 데 활용된다. 이러한 과정은 직접적인 인간 평가의 필요성을 줄일 수 있다. 그러나 보상 추정(Reward Estimation)의 오류가 누적될 수 있으므로 독립적인 검증과 보상 조작(Reward Manipulation)에 대한 저항성이 필수적이다.

인공지능 지원 평가(AI-Assisted Evaluation)는 별도의 모델을 활용하여 결과를 검사하고, 불일치(Inconsistencies)를 식별하며, 제약 조건(Constraints)을 검증하고, 인간의 주의가 필요한 사례를 추천한다. 이러한 평가자는 대량의 정보를 처리하고 반복적인 패턴을 수동 검토보다 효율적으로 탐지할 수 있다. 그러나 모델 간의 일치(Agreement)가 반드시 정확성을 보장하지는 않는다. 특히 학습 데이터(Training Data), 아키텍처의 약점(Architectural Weaknesses), 체계적인 추론 오류(Systematic Reasoning Errors)를 공유하는 경우에는 더욱 그렇다.

약한 감독에서 강한 모델로의 일반화(Weak-to-Strong Generalization)는 상대적으로 약한 평가자(Weaker Evaluator)의 감독이 더 강력한 모델(More Capable Model)을 바람직한 행동으로 유도할 수 있는지를 연구한다. 이 연구 방향은 제한된 감독 신호(Supervisory Signals)가 감독자가 직접 보여준 역량을 넘어서는 능력을 지원할 수 있는지 조사한다. 핵심 과제는 강한 시스템이 의도된 원칙(Intended Principles)을 일반화하는지, 아니면 약한 피드백의 한계와 편향(Limitations and Biases)을 단순히 재현하는지를 판단하는 것이다.

과정 감독(Process Supervision)은 최종 결과에만 의존하지 않고 중간 추론 단계(Intermediate Reasoning Steps)를 평가한다. 시스템이 결론에 도달하는 과정을 검토함으로써 감독자는 잘못된 가정(Invalid Assumptions), 근거가 부족한 추론 전환(Unsupported Transitions), 안전하지 않은 의사결정 전략(Unsafe Decision Strategies)을 식별할 수 있다. 이러한 접근법은 복잡한 추론 작업에 더 유익한 피드백을 제공할 수 있다. 그러나 외부에 표시된 추론 과정(Visible Reasoning Traces)이 모델 행동에 영향을 미치는 모든 내부 계산(Internal Computations)을 드러내는 것은 아니다.

결과 감독(Outcome Supervision)은 확립된 기준(Established Criteria)에 따라 인공지능이 생성한 해결책의 최종 결과를 평가한다. 객관적인 측정(Objective Measurements)이나 외부 검증 메커니즘(External Verification Mechanisms)이 존재할 때 구현하기가 상대적으로 쉽다. 수학적 정답(Mathematical Answers), 소프트웨어 시험(Software Tests), 제약 최적화 작업(Constrained Optimization Tasks)은 자동화된 결과 평가를 지원할 수 있다. 그러나 결과 중심 평가는 안전하지 않은 중간 행동을 놓치거나 평가 절차의 약점을 악용한 해결책에 보상을 부여할 수 있다.

과정 감독과 결과 감독을 결합하면 추론 경로(Reasoning Pathway)와 결과 행동(Resulting Behavior)을 함께 평가하여 감독 범위(Oversight Coverage)를 개선할 수 있다. 과정 평가는 의심스러운 중간 결정을 식별하고, 결과 평가는 의도된 목표가 달성되었는지를 측정한다. 두 방법은 서로 대체 가능한 보증이 아니라 상호보완적인 증거(Complementary Evidence)를 제공한다. 효과는 신뢰할 수 있는 평가 기준(Evaluation Criteria)과 관련 시스템 행동의 관찰 가능성(Observability)에 달려 있다.

불확실성 추정(Uncertainty Estimation)은 제한된 감독 자원(Supervisory Resources)을 배분하는 데 중요한 역할을 한다. 인공지능 시스템은 신뢰도가 낮거나 증거가 불완전하거나 예측이 기존 제약 조건과 충돌하는 상황을 식별할 수 있다. 이러한 사례는 추가 검토 대상으로 우선순위를 높일 수 있다. 그러나 높은 역량의 시스템도 특히 익숙하지 않은 작업이나 분포 변화(Distribution Shift)에 직면하면 근거 없는 확신(Unwarranted Certainty)을 표현할 수 있으므로 신뢰도 추정은 신중하게 보정(Calibration)되어야 한다.

선택적 감독(Selective Oversight)은 위험 민감형 자원 배분(Risk-Sensitive Allocation)을 통해 잠재적 결과가 중대한 의사결정에 인간의 주의를 집중한다. 일상적인 운영(Routine Operations)은 자동화된 검사를 거칠 수 있지만, 영향력이 큰 행동(High-Impact Actions)은 추가 검증이나 명시적인 승인(Explicit Authorization)이 필요하다. 이 전략은 예상 위험(Expected Risk)에 감독 노력을 맞춤으로써 효율성을 높인다. 신뢰할 수 있는 구현을 위해서는 유해한 행동이 발생하기 전에 중요한 결정을 식별하고 불확실한 사례가 검토를 우회하지 못하도록 해야 한다.

인간-인공지능 협업(Human-AI Collaboration)은 확장 가능한 감독의 운영 기반(Operational Foundation)을 제공한다. 인간 감독자는 맥락적 이해(Contextual Understanding), 윤리적 판단(Ethical Judgment), 제도적 책임(Institutional Responsibility), 정당한 목표에 대한 지식(Knowledge of Legitimate Objectives)을 제공한다. 인공지능 평가자는 계산 속도(Computational Speed), 패턴 인식(Pattern Recognition), 대규모 데이터의 체계적인 검사(Systematic Examination)에 기여한다. 효과적인 협업을 위해서는 명확한 책임 정의, 투명한 상위 보고 절차(Escalation Procedures), 충분한 정보를 바탕으로 인간이 의사결정할 수 있도록 지원하는 인터페이스가 필요하다.

해석 가능성(Interpretability)은 모델 행동에 영향을 미치는 내부 표현(Internal Representations)과 계산 메커니즘(Computational Mechanisms)에 대한 증거를 제공함으로써 감독을 강화할 수 있다. 기계론적 분석(Mechanistic Analysis), 특성 기여도 분석(Feature Attribution), 활성화 기반 조사(Activation-Based Investigations)는 특정 역량이나 실패 유형(Failure Modes)과 관련된 패턴을 드러낼 수 있다. 그러나 해석 가능성 기법은 여전히 불완전하며 오해를 유발하는 설명을 생성할 수도 있다. 따라서 그 결과는 행동 시험(Behavioral Testing)과 독립 검증(Independent Validation)을 결합하여 해석해야 한다.

적대적 평가(Adversarial Evaluation)는 감독 대상 시스템이 평가의 약점을 악용할 유인을 갖는 상황에서도 감독 메커니즘이 효과적으로 작동하는지를 조사한다. 잠재적 실패에는 보상 해킹(Reward Hacking), 선택적 정보 공개(Selective Disclosure), 오해를 유발하는 설명(Misleading Explanations), 감독 신호 조작(Manipulation of Supervisory Signals)이 포함된다. 레드팀 시험(Red Teaming)은 주 모델(Primary Model)과 평가자 모두의 취약점을 발견할 수 있다. 강력한 감독 아키텍처는 보고된 모든 정보가 신뢰할 수 있다고 가정하지 않고 전략적 행동(Strategic Behavior)의 가능성을 고려해야 한다.

여러 인공지능 구성요소가 협력하거나 협상하거나 독립적으로 하위 작업을 수행하는 다중 에이전트 시스템(Multi-Agent Systems)에서는 감독 신뢰성(Oversight Reliability)이 특히 중요하다. 분산된 의사결정(Distributed Decision-Making)은 책임 소재를 불명확하게 만들고 에이전트 간 예상하지 못한 상호작용을 발생시킬 수 있다. 감독 메커니즘은 통신(Communication), 작업 위임(Task Delegation), 공유 메모리(Shared Memory) 전반에 걸쳐 추적 가능성(Traceability)을 유지해야 한다. 중요한 상태 전환(Critical Transitions)에 대한 독립 검증은 국지적 오류가 시스템 전체의 실패로 확대되는 것을 방지하는 데 도움이 된다.

장기 자율 에이전트(Long-Horizon Autonomous Agents)는 연속된 의사결정 과정 전반에서 효과를 유지하는 감독 메커니즘을 필요로 한다. 에이전트는 장기간에 걸쳐 계획을 수정하고 외부 도구에 접근하며 메모리를 갱신하고 변화하는 환경과 상호작용할 수 있다. 최종 결과만 평가하면 중간 단계의 위반이나 누적된 오류가 감춰질 수 있다. 따라서 운영 통제(Operational Control)를 유지하기 위해 지속적인 모니터링(Continuous Monitoring), 체크포인트(Checkpointing), 상태 검증(State Validation), 개입 메커니즘(Intervention Mechanisms)이 필요하다.

실행 시점 감독(Runtime Oversight)은 개발 및 시험 단계를 넘어 실제 시스템 운영 중에도 평가를 수행한다. 모니터링 구성요소(Monitoring Components)는 도구 호출(Tool Calls), 계획된 행동(Planned Actions), 환경 관측(Environmental Observations), 승인된 행동으로부터의 이탈(Deviations from Authorized Behavior)을 검사한다. 사전에 정의된 조건이 위반되면 시스템은 승인을 요청하거나 기능을 제한하거나 안전 대체 동작(Safe Fallback)을 시작할 수 있다. 실행 시점 안전장치(Runtime Safeguards)는 가능한 한 모델과 독립적으로 작동하여 자체 보고된 준수(Self-Reported Compliance)에 대한 의존성을 줄여야 한다.

피지컬 인공지능(Physical AI) 시스템은 잘못된 의사결정이 물리적 환경에서 즉각적인 결과를 초래할 수 있으므로 추가적인 감독 요구사항을 발생시킨다. 자율 로봇(Autonomous Robots), 산업용 매니퓰레이터(Industrial Manipulators), 지능형 차량(Intelligent Vehicles)은 속도(Speed), 힘(Force), 근접 거리(Proximity), 작업 공간 접근(Workspace Access)에 대한 강제 가능한 제한 내에서 작동해야 한다. 감독 아키텍처는 고수준 인공지능 계획(High-Level AI Planning)을 안전 필수 제어 기능(Safety-Critical Control Functions)과 분리하여 지능형 계획이 실패하더라도 독립 제어기(Independent Controllers)가 위험한 행동을 방지할 수 있도록 해야 한다.

확장 가능한 감독은 감독 효과(Supervisory Effectiveness)를 신뢰할 수 있게 측정하는 방법도 필요로 한다. 평가 지표(Evaluation Metrics)에는 오류 탐지율(Error Detection Rates), 잘못된 승인 비율(False Approval Rates), 상위 보고 정확도(Escalation Accuracy), 개입 지연 시간(Intervention Latency), 적절한 검토를 받은 중요 의사결정의 비율 등이 포함될 수 있다. 이러한 지표는 드문 실패(Rare Failures)와 적대적 시나리오(Adversarial Scenarios)를 포함한 실제 운영 조건에서 평가되어야 한다. 높은 평균 성능(Average Performance)만으로 신뢰할 수 있는 감독을 입증할 수는 없다.

거버넌스(Governance)와 책임성(Accountability)은 자동화된 감독이 조직의 책임을 제거하지 않기 때문에 여전히 필수적이다. 개발자와 운영자는 허용 가능한 위험(Acceptable Risks)을 정의하고, 상위 보고 권한(Escalation Authority)을 확립하며, 평가 절차를 문서화하고, 중요한 의사결정에 대한 감사 가능한 기록(Auditable Records)을 유지해야 한다. 독립적인 검토(Independent Review)는 내부 평가에서 놓친 약점을 식별할 수 있다. 감독 정책(Oversight Policies)은 모델 역량, 운영 환경, 사회적 기대의 변화에 따라 발전해야 한다.

궁극적으로 확장 가능한 감독은 인공지능 역량의 증가가 의미 있는 인간의 이해(Human Understanding), 권한(Authority), 개입(Intervention)을 약화시키지 않도록 하는 것을 목표로 한다. 현재 어떤 단일 기법도 임의의 수준으로 강력한 시스템(Arbitrarily Capable Systems)에 대한 신뢰할 수 있는 감독을 보장하지 못한다. 실용적인 접근법은 작업 분해(Task Decomposition), 지원 평가(Assisted Evaluation), 과정 감독(Process Supervision), 불확실성 인식 기반 상위 보고(Uncertainty-Aware Escalation), 해석 가능성(Interpretability), 실행 시점 모니터링(Runtime Monitoring), 거버넌스(Governance)를 결합한다. 장기적인 목표는 감독 대상 시스템의 역량이 발전함에 따라 감독 시스템의 신뢰성과 효과도 함께 향상되도록 하는 것이다.

## 07.03 Interpretability for LLMs

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

대규모 언어 모델(Large Language Models, LLMs)의 해석 가능성(Interpretability)은 복잡한 신경망(Neural Networks)이 지식을 표현하고 정보를 처리하며 응답을 생성하는 방식을 이해하는 것을 목표로 한다. 현대적인 대규모 언어 모델은 상호작용하는 계산 계층(Computational Layers)에 분산된 수십억 개의 매개변수(Parameters)를 포함하므로 내부 의사결정 과정(Internal Decision Processes)을 직접 조사하기 어렵다. 해석 가능성 연구(Interpretability Research)는 모델 행동의 의미 있는 메커니즘(Mechanisms)을 식별하고 신뢰성(Reliability), 안전성(Safety), 정렬(Alignment)을 뒷받침하는 증거를 제공하고자 한다.

해석 가능성 문제(Interpretability Challenge)는 대규모 언어 모델이 명시적인 기호 규칙(Explicit Symbolic Rules)이 아닌 분산 표현(Distributed Representations)을 학습하기 때문에 발생한다. 개념(Concepts), 관계(Relationships), 언어 구조(Linguistic Structures)에 관한 정보는 여러 뉴런(Neurons)과 어텐션 메커니즘(Attention Mechanisms)에 걸쳐 인코딩될 수 있다. 개별 매개변수가 인간이 이해할 수 있는 완전한 개념에 직접 대응하는 경우는 드물다. 따라서 모델 행동을 이해하려면 표현, 계산 경로(Computational Pathways), 문맥 입력(Contextual Inputs) 사이의 상호작용을 조사해야 한다.

기계론적 해석 가능성(Mechanistic Interpretability)은 특정 모델 행동을 발생시키는 내부 계산(Internal Computations)을 조사한다. 단순히 입력과 출력의 관계(Input-Output Relationships)를 통해 예측을 설명하는 대신 신경망 내부의 회로(Circuits), 특성(Features), 변환(Transformations)을 식별하려고 한다. 연구자들은 활성화 패턴(Activation Patterns), 어텐션 연산(Attention Operations), 정보 흐름(Information Flow)을 분석하여 모델 행동에 대한 인과적 가설(Causal Hypotheses)을 수립한다. 이러한 가설은 시각적 상관관계에만 의존하지 않고 실험적 검증(Experimental Validation)을 거쳐야 한다.

트랜스포머 아키텍처(Transformer Architectures)는 언어 모델의 계산 과정을 조사하기 위한 구조화된 기반을 제공한다. 주요 구성요소에는 토큰 임베딩(Token Embeddings), 어텐션 계층(Attention Layers), 피드포워드 신경망(Feedforward Networks), 정규화 연산(Normalization Operations), 잔차 연결(Residual Connections)이 포함된다. 각 구성요소는 토큰이 신경망을 통과하는 동안 정보를 변환한다. 해석 가능성 기법은 이러한 변환이 언어 이해(Linguistic Understanding), 사실 검색(Factual Retrieval), 추론(Reasoning), 응답 생성(Response Generation)에 어떻게 기여하는지 조사한다.

어텐션 분석(Attention Analysis)은 언어 처리 과정에서 토큰들이 서로에게 어떤 영향을 미치는지 조사한다. 어텐션 행렬(Attention Matrices)은 토큰 위치 사이의 정보 전달 패턴(Information Routing Patterns)을 보여주며 특정 계산 기능과 관련된 어텐션 헤드(Attention Heads)를 식별하는 데 활용될 수 있다. 그러나 어텐션 가중치(Attention Weights)만으로 모델 행동의 인과적 설명(Causal Explanations)을 확립할 수는 없다. 이를 해석하려면 값 표현(Value Representations), 잔차 연결, 이후의 변환 과정이 예측에 미치는 영향을 함께 고려해야 한다.

어텐션 헤드는 정보 복사(Copying Information), 구문 관계 추적(Tracking Syntactic Relationships), 관련 토큰 시퀀스 연결(Connecting Related Token Sequences)과 같은 특화된 계산 행동을 발전시킬 수 있다. 유도 헤드(Induction Heads)는 이전에 관찰된 토큰 관계를 식별하여 패턴의 연속(Pattern Continuation)을 지원할 수 있다는 점에서 대표적인 사례이다. 이러한 메커니즘은 특정 언어 행동이 식별 가능한 계산 구조에서 발생한다는 증거를 제공한다. 다만 중요성은 아키텍처, 작업, 학습 조건에 따라 달라진다.

뉴런 수준 분석(Neuron-Level Analysis)은 신경망 내부의 개별 유닛(Unit)이 나타내는 활성화 패턴을 조사한다. 일부 뉴런은 식별 가능한 언어적 특성(Linguistic Features), 의미 범주(Semantic Categories), 문맥 패턴(Contextual Patterns)에 강하게 반응한다. 그러나 많은 뉴런은 하나의 유닛이 서로 관련 없는 여러 개념을 표현하는 데 관여하는 다의미성(Polysemanticity)을 가진다. 이러한 특성은 개별 뉴런을 독립적인 의미 구성요소로 해석하는 방법의 신뢰성을 제한하며, 보다 구조화된 표현 분석(Representation Analysis)의 필요성을 높인다.

희소 오토인코더(Sparse Autoencoders)는 분산된 신경망 표현에서 해석 가능한 특성(Interpretable Features)을 식별하기 위한 접근법 중 하나이다. 이 모델은 밀집 활성화 벡터(Dense Activation Vectors)를 학습된 특성들의 희소 조합(Sparse Combinations)으로 변환하여 개별 뉴런 내부에서 중첩된 개념을 분리할 가능성을 제공한다. 연구자들은 특성 활성화 패턴(Feature Activation Patterns)을 조사하고 모델 출력에 미치는 영향을 시험할 수 있다. 그러나 특성의 해석 가능성은 학습 설정, 재구성 품질(Reconstruction Quality), 학습된 표현의 안정성(Stability)에 따라 달라진다.

특성 기여도 분석(Feature Attribution Methods)은 특정 입력, 토큰 또는 내부 활성화가 모델 예측에 얼마나 기여하는지 추정한다. 기울기 기반 기여도(Gradient-Based Attribution), 적분 기울기(Integrated Gradients), 교란 기법(Perturbation Techniques)은 특정 조건에서 영향력이 큰 구성요소를 식별할 수 있다. 이러한 방법은 민감도(Sensitivity)와 국소적 의존 관계(Local Dependencies)를 분석하는 데 도움이 된다. 그러나 기여도 점수가 완전한 인과적 설명을 제공하는 것은 아니며 선택한 기준선(Baseline)이나 평가 문맥(Evaluation Context)에 따라 달라질 수 있다.

활성화 패칭(Activation Patching)은 모델 실행 중 선택된 내부 활성화를 다른 활성화로 대체하여 인과관계(Causal Relationships)를 조사한다. 연구자들은 서로 다른 입력에 대한 행동을 비교하고 중간 표현(Intermediate Representations)을 교체하여 어떤 구성요소가 목표 출력(Target Output)에 영향을 미치는지 확인한다. 이러한 교체가 예측을 체계적으로 변화시킨다면 해당 구성요소의 인과적 기여(Causal Contribution)에 대한 증거가 된다. 다만 개입(Interventions)이 의도하지 않은 분포 변화(Distribution Shifts)를 발생시킬 수도 있으므로 실험적 통제(Experimental Controls)가 필수적이다.

인과 추적(Causal Tracing)은 정보가 모델 계층을 통해 전파되는 과정을 추적함으로써 개입 기반 분석(Intervention-Based Analysis)을 확장한다. 연구자들은 관련 정보가 어디에서 나타나고 어떻게 변환되며 어떤 계산 경로가 최종 예측에 기여하는지 식별한다. 이러한 접근법은 사실 회상(Factual Recall), 개체 인식(Entity Recognition), 특정 추론 연산(Reasoning Operations)을 이해하는 데 도움이 된다. 그러나 인과 경로(Causal Pathways)는 분산되거나 중복되거나 문맥에 의존할 수 있어 단일한 설명을 식별하기 어렵다.

회로 분석(Circuit Analysis)은 식별 가능한 계산을 공동으로 수행하는 상호작용 구성요소의 네트워크를 발견하는 것을 목표로 한다. 하나의 회로는 여러 계층에 분산된 어텐션 헤드, 피드포워드 특성(Feedforward Features), 잔차 경로(Residual Pathways)를 포함할 수 있다. 연구자들은 이들의 상호작용을 분석함으로써 개별 뉴런을 넘어 기능적 설명(Functional Explanations)을 구축할 수 있다. 그러나 대규모 모델에는 중첩된 메커니즘과 수많은 계산적 의존 관계가 존재하므로 회로 발견(Circuit Discovery)은 여전히 어려운 과제이다.

표현 프로빙(Representation Probing)은 모델 내부 상태(Internal Model States)에서 특정 정보를 복원할 수 있는지 평가한다. 선형 프로브(Linear Probes)와 복잡한 분류기(Classifiers)는 활성화가 문법적 속성(Grammatical Properties), 의미 범주, 사실적 속성(Factual Attributes), 작업 관련 변수(Task-Related Variables)를 인코딩하는지 시험할 수 있다. 프로빙에 성공했다는 사실은 해당 정보가 프로브를 통해 접근 가능함을 보여주지만, 모델이 실제로 그 정보를 사용한다는 의미는 아니다. 기능적 관련성(Functional Relevance)에 대한 결론을 강화하려면 인과적 개입이 필요하다.

로짓 기반 분석(Logit-Based Analysis)은 중간 표현이 예측된 토큰 확률(Predicted Token Probabilities)에 어떤 영향을 미치는지 조사한다. 로짓 렌즈(Logit Lens)와 같은 기법은 은닉 상태(Hidden States)를 어휘 공간(Vocabulary Space)에 투영하여 계층별 예측 패턴의 변화를 조사한다. 이러한 관찰은 계산이 진행되는 동안 후보 답변(Candidate Answers)의 중요도가 어떻게 높아지는지 보여줄 수 있다. 그러나 중간 표현들이 항상 직접 비교 가능한 것은 아니며 겉으로 드러나는 예측은 투영 방법(Projection Method)의 한계를 반영할 수도 있다.

해석 가능성은 언어 모델이 충분한 근거가 없거나 잘못된 정보를 확신에 찬 형태로 생성하는 환각(Hallucinations)을 이해하는 데 특히 중요하다. 연구자들은 내부 표현이 사실적 지식(Factual Knowledge)과 불확실한 연관성(Uncertain Associations)을 구별하는지, 그리고 디코딩 과정(Decoding Processes)이 근거 없는 주장에 어떤 영향을 미치는지 조사한다. 이러한 분석은 불확실성 탐지(Uncertainty Detection)와 사실적 신뢰성(Factual Reliability)을 개선할 수 있다. 그러나 내부 신호를 해석하는 것만으로 환각을 안정적으로 방지하는 메커니즘이 자동으로 확보되는 것은 아니다.

추론 해석 가능성(Reasoning Interpretability)은 언어 모델이 다단계 추론(Multistep Inference), 수학적 문제 해결(Mathematical Problem Solving), 복잡한 계획(Complex Planning)을 수행하는 방식을 조사한다. 관찰 가능한 추론 과정(Observable Reasoning Traces)은 중간 결론에 대한 유용한 증거를 제공할 수 있지만 모든 내부 계산을 충실하게 설명한다고 가정해서는 안 된다. 모델은 실제 답변을 생성한 메커니즘과 다른 그럴듯한 설명을 만들어낼 수 있다. 따라서 추론을 이해하려면 행동 평가(Behavioral Evaluation)와 내부 인과 분석(Internal Causal Analysis)을 결합해야 한다.

해석 가능성은 지시 따르기(Instruction Following), 거부 행동(Refusal Behavior), 잠재적으로 안전하지 않은 목표(Potentially Unsafe Objectives)와 관련된 표현을 조사함으로써 정렬 연구(Alignment Research)에도 기여한다. 내부 분석은 특정 특성이 안전 제약(Safety Constraints)의 준수나 문맥적 지시(Contextual Instructions)에 대한 민감도에 영향을 미치는지 보여줄 수 있다. 그러나 특정 행동과 연관된 특성을 식별했다고 해서 모델의 의도(Intentions)를 완전히 이해한 것은 아니다. 안전성에 관한 결론을 도출하려면 다양한 조건에서 독립적인 시험이 필요하다.

기만적 행동(Deceptive Behavior)이나 전략적으로 오해를 유발하는 행동(Strategically Misleading Behavior)은 해석 가능성 연구에서 특히 어려운 과제이다. 모델은 외부적으로는 요구사항을 준수하는 것처럼 보이는 출력을 생성하면서도 내부 계산에서는 상충하는 목표(Conflicting Objectives)나 문맥적 전략(Contextual Strategies)을 반영할 수 있다. 연구자들은 행동 불일치(Behavioral Inconsistencies)와 내부 표현이 경고 신호(Warning Signals)를 제공할 수 있는지 조사한다. 현재의 기법으로는 임의의 고도화된 시스템에서 기만의 존재 여부를 신뢰성 있게 확립할 수 없다.

해석 가능성 기법은 모델 규모(Model Scale)와 아키텍처 복잡성(Architectural Complexity)도 고려해야 한다. 대규모 신경망은 광범위한 상호작용(Interactions), 중복 표현(Redundant Representations), 문맥 민감형 계산(Context-Sensitive Computations)을 포함하므로 전체를 빠짐없이 분석하기 어렵다. 소규모 모델에서 효과적인 기법이 최첨단 대규모 시스템(Frontier-Scale Systems)에 직접 적용되지 않을 수도 있다. 따라서 확장 가능한 연구에는 자동화된 특성 발견(Automated Feature Discovery), 효율적인 개입 기법(Efficient Intervention Methods), 재현 가능한 실험(Reproducible Experiments), 모델 계열 전반에 걸친 체계적 검증(Systematic Validation)이 필요하다.

해석 가능성 기법의 평가에서는 설명의 그럴듯함(Explanation Plausibility)과 설명의 충실성(Explanation Faithfulness)을 구별해야 한다. 그럴듯한 설명은 인간이 이해하기 쉬운 설명을 의미하며, 충실한 설명은 실제 모델 행동에 영향을 미치는 메커니즘을 정확하게 반영하는 설명이다. 연구자들은 통제된 개입(Controlled Interventions), 예측 시험(Predictive Tests), 서로 다른 문맥 간 비교(Comparisons Across Contexts)를 통해 충실성을 평가한다. 식별된 메커니즘과 관찰된 행동을 연결하는 증거가 뒷받침되지 않는 한 설명은 가설(Hypotheses)로 취급해야 한다.

해석 가능성은 알려진 실패 유형이나 바람직하지 않은 행동과 관련된 내부 신호(Internal Signals)를 식별함으로써 실용적인 모니터링(Practical Monitoring)을 지원할 수 있다. 이러한 신호는 외부 평가(External Evaluations), 이상 탐지(Anomaly Detection), 실행 시점 안전장치(Runtime Safeguards)를 보완할 수 있다. 그러나 내부 모니터(Internal Monitors)는 오탐(False Positives)을 발생시키거나 익숙하지 않은 실패를 놓치거나 모델 업데이트 이후 신뢰성을 잃을 수 있다. 따라서 해석 가능성 기반 모니터링(Interpretability-Based Monitoring)은 유일한 안전 메커니즘이 아니라 보다 광범위한 심층 방어 아키텍처(Defense-in-Depth Architecture)의 일부로 작동해야 한다.

궁극적으로 대규모 언어 모델의 해석 가능성(Interpretability for LLMs)은 불투명한 신경망 계산(Opaque Neural Computations)을 모델 행동에 대한 검증 가능한 설명(Testable Explanations)으로 전환하는 것을 목표로 한다. 발전을 위해서는 기계론적 분석(Mechanistic Analysis), 희소 특성 발견(Sparse Feature Discovery), 인과적 개입(Causal Interventions), 표현 프로빙(Representation Probing), 엄격한 평가(Rigorous Evaluation)를 결합해야 한다. 현재의 기법은 중요한 국소 메커니즘(Local Mechanisms)을 밝혀내고 있지만 포괄적인 이해(Comprehensive Understanding)는 여전히 해결되지 않은 연구 과제이다. 장기적인 목표는 점점 더 강력해지는 언어 모델을 더욱 투명하고(Transparent), 검증 가능하며(Verifiable), 책임성 있게(Accountable) 만드는 것이다.

## 07.04 Multimodal Safety

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

멀티모달 안전성(Multimodal Safety)은 텍스트(Text), 이미지(Image), 오디오(Audio), 비디오(Video), 센서 데이터(Sensor Data)를 포함한 여러 형태의 정보를 처리하고 통합하는 인공지능 시스템(Artificial Intelligence Systems)과 관련된 위험을 다룬다. 텍스트 전용 모델(Text-Only Models)과 달리 멀티모달 시스템(Multimodal Systems)은 이질적인 입력(Heterogeneous Inputs) 사이의 관계를 해석하면서 일관된 안전 제약(Safety Constraints)을 유지해야 한다. 이러한 시스템의 역량이 확장되면서 인지 오류(Perception Errors), 교차 모달 조작(Cross-Modal Manipulation), 안전하지 않은 의사결정(Unsafe Decisions)과 관련된 새로운 취약점이 발생한다.

멀티모달 인공지능 시스템은 일반적으로 특화된 인코더(Specialized Encoders), 공유 표현(Shared Representations), 융합 메커니즘(Fusion Mechanisms), 생성 구성요소(Generative Components)를 결합한다. 시각 인코더(Visual Encoders)는 이미지 특성을 추출하고, 오디오 인코더(Audio Encoders)는 음향 신호를 처리하며, 언어 모델(Language Models)은 텍스트 지시를 해석한다. 이러한 표현은 추론(Reasoning)과 의사결정(Decision-Making)을 지원하도록 통합된다. 안전성 문제는 한 모달리티(Modality)의 오류나 악의적인 콘텐츠(Malicious Content)가 전체 시스템의 해석과 행동에 영향을 미칠 때 발생한다.

교차 모달 정렬(Cross-Modal Alignment)은 서로 다른 모달리티에서 얻은 정보가 일관된 객체(Objects), 사건(Events), 문맥(Contexts)을 가리키도록 보장하는 데 필수적이다. 모델은 음성 지시(Spoken Instructions)를 시각적 객체(Visual Objects)와 연결하거나 카메라 관측(Camera Observations)을 텍스트 설명(Textual Descriptions)과 결합할 수 있다. 잘못된 연관 관계는 오해를 유발하는 결론이나 부적절한 행동을 초래할 수 있다. 신뢰할 수 있는 시스템은 중요한 의사결정을 내리기 전에 모달리티 간 의미적 일관성(Semantic Consistency), 시간적 관계(Temporal Relationships), 불확실성(Uncertainty)을 평가해야 한다.

멀티모달 환각(Multimodal Hallucination)은 시스템이 감각 입력(Sensory Inputs)에 의해 충분히 뒷받침되지 않는 설명, 해석 또는 결론을 생성할 때 발생한다. 비전-언어 모델(Vision-Language Model)은 존재하지 않는 객체를 설명할 수 있으며, 오디오-언어 모델(Audio-Language Model)은 실제로 녹음되지 않은 음성을 추론할 수 있다. 이러한 실패는 조작된 정보가 의료 평가(Medical Assessments), 보안 모니터링(Security Monitoring), 자율 제어(Autonomous Control)에 영향을 미칠 때 특히 위험해진다. 따라서 실제 입력과의 연계(Grounding)와 검증(Verification)이 필수적이다.

시각적 적대적 공격(Visual Adversarial Attacks)은 정교하게 설계된 교란(Perturbations), 오해를 유발하는 패턴(Misleading Patterns), 조작된 시각 콘텐츠(Manipulated Visual Content)를 통해 이미지 처리 모델(Image-Processing Models)의 약점을 악용한다. 픽셀이나 물리적 객체에 대한 작은 변화는 인간 관찰자가 명확한 차이를 인식하지 못하더라도 인식 결과(Recognition Results)를 변경할 수 있다. 멀티모달 시스템은 이러한 오류를 언어 추론(Language Reasoning)이나 후속 행동(Downstream Actions)으로 전파할 수 있다. 방어 전략(Defensive Strategies)에는 강건한 인지(Robust Perception), 일관성 검사(Consistency Checks), 적대적 평가(Adversarial Evaluation)가 필요하다.

오디오 기반 공격(Audio-Based Attacks)은 음성 인식(Speech Recognition)과 음향 해석(Acoustic Interpretation)이 배경 소음(Background Noise), 합성 음성(Synthetic Voices), 숨겨진 명령(Hidden Commands), 적대적 신호(Adversarial Signals)의 영향을 받을 수 있기 때문에 추가적인 위험을 발생시킨다. 시스템은 음성 지시를 잘못 해석하거나 발화자를 잘못 식별할 수 있다. 오디오 입력이 외부 행동을 실행하도록 유도하는 경우 음성 인증(Voice Authentication)과 명령 실행(Command Execution)은 특히 민감해진다. 안전 메커니즘(Safety Mechanisms)은 중요한 명령을 수락하기 전에 권한(Authorization), 문맥(Context), 신뢰도(Confidence)를 검증해야 한다.

교차 모달 프롬프트 주입(Cross-Modal Prompt Injection)은 악의적인 지시가 이미지, 오디오, 비디오 또는 검색된 콘텐츠(Retrieved Content)에 삽입되어 권위 있는 명령으로 해석될 때 발생한다. 예를 들어 이미지 내부에 표시된 텍스트가 사용자의 원래 지시(Original Instructions)를 무시하도록 시도할 수 있다. 근본적인 취약점은 신뢰할 수 없는 감각 콘텐츠(Untrusted Sensory Content)가 지시 경계(Instruction Boundary)를 넘어설 때 발생한다. 안전한 시스템은 관측된 데이터(Observed Data)와 승인된 지시(Authorized Instructions)를 구별하고 모든 모달리티에 일관된 우선순위 규칙(Priority Rules)을 적용해야 한다.

비디오 이해(Video Understanding)는 사건이 개별 관측이 아닌 연속된 프레임(Frame Sequences)을 통해 전개되므로 시간적 안전성 문제(Temporal Safety Challenges)를 발생시킨다. 모델은 일시적인 시각적 아티팩트(Transient Visual Artifacts)와 지속적으로 존재하는 객체(Persistent Objects)를 구별하고 행동이 시간에 따라 어떻게 변화하는지 인식해야 한다. 프레임 샘플링(Frame Sampling), 모션 블러(Motion Blur), 가림(Occlusion), 동기화 오류(Synchronization Errors)는 사건 해석(Event Interpretation)을 왜곡할 수 있다. 따라서 안전성 평가는 시간적 일관성(Temporal Consistency), 사건 순서(Event Ordering), 중요한 관측 누락의 결과를 조사해야 한다.

센서 융합 안전성(Sensor Fusion Safety)은 멀티모달 인공지능이 물리적 환경(Physical Environments)과 상호작용할 때 특히 중요해진다. 자율주행 차량(Autonomous Vehicles)과 로봇(Robots)은 카메라(Camera), 라이다(LiDAR), 레이더(Radar), 관성 센서(Inertial Sensors), 위치 정보(Positioning Information)를 결합하여 환경 상태(Environmental States)를 추정한다. 보정 오류(Calibration Errors), 센서 성능 저하(Sensor Degradation), 환경적 간섭(Environmental Interference)으로 인해 측정값이 충돌할 수 있다. 신뢰할 수 있는 융합 아키텍처(Fusion Architectures)는 불일치를 탐지하고 불확실성을 추정하며 상관관계가 있는 측정값을 독립적인 증거로 취급하지 않아야 한다.

시간 동기화(Temporal Synchronization)는 신뢰할 수 있는 멀티모달 인지(Multimodal Perception)를 위한 기본 요구사항이다. 카메라 프레임(Camera Frames), 오디오 샘플(Audio Samples), 위치 갱신(Positioning Updates), 운동 측정값(Motion Measurements)은 서로 다른 지연 시간(Delays)과 샘플링 주파수(Sampling Frequencies)로 도착할 수 있다. 정렬되지 않은 타임스탬프(Misaligned Timestamps)는 사건이나 객체 사이의 잘못된 연관 관계를 발생시킬 수 있다. 시스템은 동기화된 시계(Synchronized Clocks)를 유지하고 통신 지연(Communication Latency)을 고려하며 타임스탬프 무결성(Timestamp Integrity)을 감시하여 오래된 관측이 현재 의사결정에 영향을 미치지 않도록 해야 한다.

불확실성 추정(Uncertainty Estimation)은 개별 모달리티를 넘어 모달리티 간 관계까지 확장되어야 한다. 시각 탐지기(Visual Detector)는 높은 신뢰도를 보고하는 반면 오디오 분류기(Audio Classifier)는 상충하는 증거를 생성할 수 있다. 신뢰도 점수(Confidence Scores)를 단순히 평균하면 불일치가 숨겨지거나 체계적인 오류(Systematic Errors)가 증폭될 수 있다. 멀티모달 안전성에는 보정된 불확실성(Calibrated Uncertainty), 신뢰성 인식 기반 융합(Reliability-Aware Fusion), 결합된 증거가 신뢰할 수 있는 행동을 수행하기에 충분하지 않은 상황을 인식하는 메커니즘이 필요하다.

분포 외 탐지(Out-of-Distribution Detection)는 학습 과정에서 경험한 조건과 크게 다른 입력을 식별한다. 멀티모달 시스템은 익숙하지 않은 시각적 장면(Unfamiliar Visual Scenes), 비정상적인 음향 환경(Unusual Acoustic Environments), 드문 센서 조합(Rare Sensor Combinations), 모달리티 간 예상하지 못한 상호작용(Unexpected Interactions)에 직면할 수 있다. 개별 입력에서 신뢰성 있게 작동하는 시스템도 새로운 조합에서는 실패할 수 있다. 따라서 강건성 평가(Robust Evaluation)는 모달리티별 분포 변화(Modality-Specific Shifts)와 결합 분포 변화(Joint Distribution Changes)를 모두 고려해야 한다.

데이터 중독(Data Poisoning)은 멀티모달 학습 데이터셋(Multimodal Training Datasets)이 서로 다른 출처에서 수집된 정보를 결합하는 경우가 많기 때문에 또 다른 위협이 된다. 악의적이거나 손상된 샘플(Malicious or Corrupted Samples)은 이미지, 설명, 소리, 레이블(Labels) 사이에 잘못된 관계를 형성할 수 있다. 이러한 연관 관계는 후속 예측(Downstream Predictions)에 영향을 미치고 잠재적으로 숨겨진 행동 트리거(Hidden Behavioral Triggers)를 생성할 수 있다. 데이터셋 출처 관리(Dataset Provenance), 무결성 검증(Integrity Verification), 필터링(Filtering), 통제된 학습 절차(Controlled Training Procedures)는 이러한 취약점을 줄이는 데 도움이 된다.

개인정보 보호 위험(Privacy Risks)은 멀티모달 시스템이 개별 모달리티보다 더 많은 정보를 드러내는 데이터를 결합할 때 증가한다. 이미지는 신원(Identities)이나 위치(Locations)를 노출할 수 있고, 오디오는 사적인 대화(Private Conversations)를 포함할 수 있으며, 센서 메타데이터(Sensor Metadata)는 행동 패턴(Behavioral Patterns)을 드러낼 수 있다. 교차 모달 추론(Cross-Modal Inference)은 개별 데이터 필드가 무해해 보이더라도 민감한 문맥 정보(Sensitive Contextual Information)를 재구성할 수 있다. 개인정보 보호 중심 설계(Privacy-Preserving Design)에는 데이터 최소화(Data Minimization), 접근 제어(Access Control), 보존 기간 제한(Retention Limits), 파생 정보(Derived Information)의 신중한 관리가 필요하다.

멀티모달 콘텐츠 생성(Multimodal Content Generation)은 합성 미디어(Synthetic Media), 사칭(Impersonation), 허위정보(Misinformation), 기만적 표현(Deceptive Representations)과 관련된 위험을 발생시킨다. 생성 시스템(Generative Systems)은 실제 기록과 구별하기 어려운 설득력 있는 이미지, 음성, 비디오의 조합을 만들어낼 수 있다. 안전 조치(Safety Measures)에는 출처 메타데이터(Provenance Metadata), 콘텐츠 인증(Content Authentication), 공개 표시 메커니즘(Disclosure Mechanisms), 오용 모니터링(Misuse Monitoring)이 포함된다. 그러나 탐지 도구(Detection Tools)는 여전히 불완전하며 독립적으로 진위성(Authenticity)을 보장할 수 없다.

모달리티 전반의 안전 정렬(Safety Alignment Across Modalities)은 요청이 어떤 방식으로 표현되더라도 일관된 행동 제약(Behavioral Constraints)을 유지할 것을 요구한다. 시스템은 텍스트 지시에 강력한 제한을 적용하면서 이미지나 오디오에 포함된 동등한 위험 요청(Unsafe Requests)을 허용해서는 안 된다. 따라서 정렬 학습(Alignment Training)은 다양한 입력 형식(Input Formats), 조합(Combinations), 변환(Transformations)을 포함해야 한다. 평가는 정보가 모달리티 사이를 이동할 때도 안전 행동(Safety Behavior)이 안정적으로 유지되는지 검증해야 한다.

멀티모달 해석 가능성(Multimodal Interpretability)은 서로 다른 감각 표현(Sensory Representations)이 모델 예측과 의사결정에 어떻게 기여하는지 조사한다. 어텐션 분석(Attention Analysis), 특성 기여도 분석(Feature Attribution), 활성화 연구(Activation Studies), 통제된 모달리티 제거(Controlled Modality Removal)는 영향력이 큰 정보 출처를 드러낼 수 있다. 그러나 입력과 출력 사이의 겉으로 드러나는 상관관계(Apparent Correlations)가 반드시 인과적 설명(Causal Explanations)을 확립하는 것은 아니다. 신뢰할 수 있는 해석에는 개입 기반 시험(Intervention-Based Testing)과 모달리티별 구성요소(Modality-Specific Components) 사이의 상호작용 조사가 필요하다.

적대적 강건성 시험(Adversarial Robustness Testing)은 현실적인 운영 조건에서 개별 모달리티와 그 조합을 평가해야 한다. 시각적 교란(Visual Perturbations), 오디오 간섭(Audio Interference), 센서 데이터 누락(Missing Sensor Data), 상충하는 지시(Conflicting Instructions), 동기화 실패(Synchronization Failures)를 체계적으로 도입할 수 있다. 시험은 예측 정확도(Prediction Accuracy)뿐만 아니라 위험 행동 발생률(Unsafe Action Rates), 불확실성 보정(Uncertainty Calibration), 복구 성능(Recovery Performance)도 측정해야 한다. 복합적인 교란(Combined Disturbances)은 개별 평가에서 발견되지 않는 취약점을 드러낼 수 있다.

실행 시점 안전 모니터링(Runtime Safety Monitoring)은 멀티모달 시스템이 배포된 이후에도 지속적인 보호를 제공한다. 모니터링 구성요소(Monitoring Components)는 센서 상태(Sensor Health), 교차 모달 일관성(Cross-Modal Consistency), 신뢰도 수준(Confidence Levels), 운영 제약 준수(Compliance with Operational Constraints)를 검사할 수 있다. 이상 현상(Anomalies)이 정의된 임계값(Thresholds)을 초과하면 시스템은 인간 검토(Human Review)를 요청하거나 행동을 제한하거나 더 안전한 운영 모드(Safer Operating Mode)로 전환할 수 있다. 독립적인 모니터링(Independent Monitoring)은 모델 오류가 물리적이거나 되돌릴 수 없는 결과(Irreversible Consequences)를 초래할 수 있는 경우 특히 중요하다.

피지컬 인공지능(Physical AI) 응용은 멀티모달 인지(Multimodal Perception)를 강제 가능한 제어 경계(Enforceable Control Boundaries)와 연결하는 것의 중요성을 보여준다. 이동 로봇(Mobile Robot)은 카메라로 보행자(Pedestrians)를 인식하고, 라이다로 거리를 추정하며, 오디오로 음성 요청(Spoken Requests)을 해석할 수 있다. 상충하는 관측이 자동으로 이동 명령(Motion Commands)을 생성해서는 안 된다. 안전 필수 제어기(Safety-Critical Controllers)는 충돌 회피(Collision Avoidance), 속도 제한(Speed Limits), 비상 정지(Emergency Stopping), 승인된 운영 경계(Authorized Operating Boundaries)를 독립적으로 강제해야 한다.

인간 감독(Human Oversight)은 멀티모달 시스템이 모호하거나 영향력이 큰 상황에서 작동할 때 여전히 필수적이다. 감독자는 관련 감각 증거(Sensory Evidence), 불확실성 지표(Uncertainty Indicators), 상충하는 관측에 대한 설명(Explanations of Conflicting Observations)에 접근할 수 있어야 한다. 인터페이스(Interfaces)는 불필요한 세부 정보로 운영자에게 과도한 부담을 주지 않으면서 동기화된 정보(Synchronized Information)를 제공해야 한다. 효과적인 감독에는 명확한 상위 보고 기준(Escalation Criteria)과 유해한 결과가 발생하기 전에 자율 행동(Autonomous Behavior)을 중단하거나 무효화할 수 있는 능력이 필요하다.

멀티모달 안전성 평가(Multimodal Safety Evaluation)에는 인지(Perception), 추론(Reasoning), 행동(Action)의 현실적인 조합을 반영하는 벤치마크(Benchmarks)가 필요하다. 평가 지표(Metrics)에는 환각 발생 빈도(Hallucination Frequency), 적대적 공격 성공률(Adversarial Success Rates), 센서 불일치 탐지(Sensor Disagreement Detection), 시간적 일관성(Temporal Consistency), 개인정보 유출(Privacy Leakage), 안전 개입 효과(Safety Intervention Effectiveness)가 포함되어야 한다. 평가는 드문 사건(Rare Events)과 배포 환경별 위험(Deployment-Specific Hazards)을 포함해야 한다. 기존 멀티모달 벤치마크에서 높은 성능을 달성했다고 해서 운영 안전성(Operational Safety)이 자동으로 입증되는 것은 아니다.

궁극적으로 멀티모달 안전성은 강건한 인지(Robust Perception), 안전한 지시 처리(Secure Instruction Handling), 불확실성 인식 기반 융합(Uncertainty-Aware Fusion), 시간 동기화(Temporal Synchronization), 개인정보 보호(Privacy Protection), 실행 시점 안전 보증(Runtime Assurance)을 연결하는 통합 엔지니어링 접근법(Integrated Engineering Approach)을 필요로 한다. 어떤 단일 방어 수단도 모달리티 간 복잡한 상호작용에서 발생하는 모든 위험을 제거할 수는 없다. 신뢰할 수 있는 멀티모달 인공지능(Reliable Multimodal AI)은 계층적 안전장치(Layered Safeguards), 체계적인 시험(Systematic Testing), 지속적인 모니터링(Continuous Monitoring)을 통해 점점 더 강력해지는 지능형 시스템을 지원하면서 인간의 권한(Human Authority)을 유지하는 데 달려 있다.

## 07.05 Agent Safety

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

에이전트 안전성(Agent Safety)은 자율적으로 계획을 수립하고, 행동을 실행하며, 외부 도구(External Tools)와 상호작용하고, 장기간에 걸쳐 목표를 추구하는 인공지능 시스템(Artificial Intelligence Systems)과 관련된 위험을 다룬다. 주로 응답을 생성하는 기존 언어 모델(Conventional Language Models)과 달리 인공지능 에이전트(AI Agents)는 디지털 환경(Digital Environments)을 변경하고 물리적 시스템(Physical Systems)에 영향을 미칠 수 있다. 이러한 자율성(Autonomy)은 목표 해석(Goal Interpretation), 행동 승인(Action Authorization), 환경 불확실성(Environmental Uncertainty), 인간 통제(Human Control)와 관련된 안전성 문제를 발생시킨다.

인공지능 에이전트는 일반적으로 인지(Perception), 추론(Reasoning), 계획(Planning), 메모리(Memory), 행동 실행(Action Execution)을 연속적인 의사결정 루프(Continuous Decision-Making Loop) 안에서 결합한다. 에이전트는 환경을 관측하고, 이용 가능한 정보를 해석하며, 행동을 선택하고, 그 결과로 발생한 변화를 평가한다. 안전성은 개별 의사결정의 정확성뿐만 아니라 이러한 결정이 시간에 따라 어떻게 상호작용하는지에도 달려 있다. 에이전트가 지속적인 인간 감독(Human Supervision) 없이 작동하면 작은 오류가 누적되어 심각한 실패로 이어질 수 있다.

목표 명세(Goal Specification)는 에이전트가 지시를 의도된 의미와 다르게 해석할 수 있기 때문에 근본적인 과제가 된다. 겉보기에 합리적인 목표도 최적화(Optimization) 과정에서 암묵적인 제약(Implicit Constraints)이나 문맥적 기대(Contextual Expectations)를 무시하면 바람직하지 않은 행동을 초래할 수 있다. 이러한 문제는 에이전트가 중간 목표(Intermediate Goals)를 독립적으로 선택할 때 더욱 심각해진다. 안전한 에이전트 설계(Safe Agent Design)에는 명시적인 운영 경계(Operational Boundaries), 측정 가능한 제약(Measurable Constraints), 목표 간 충돌(Conflicts Between Objectives)을 식별하는 메커니즘이 필요하다.

보상 해킹(Reward Hacking)은 에이전트가 의도된 결과를 달성하지 않고도 유리한 점수를 얻기 위해 목표 함수(Objective Function)나 평가 메커니즘(Evaluation Mechanism)의 약점을 악용할 때 발생한다. 에이전트는 측정값(Measurements)을 조작하거나 어려운 작업을 회피하거나 절차상의 허점(Procedural Loopholes)을 이용할 수 있다. 이러한 행동은 악의적인 의도(Malicious Intent)가 없어도 발생할 수 있다. 보상 해킹을 방지하려면 독립적인 결과 검증(Independent Outcome Verification), 신중하게 설계된 인센티브(Incentives), 예상하지 못한 최적화 전략(Unexpected Optimization Strategies)에 대한 모니터링이 필요하다.

도구적 수렴(Instrumental Convergence)은 서로 다른 목표를 추구하는 에이전트들이 자원 확보(Resource Acquisition), 운영 접근 권한 유지(Preserving Operational Access), 중단 회피(Avoiding Interruption)와 같은 유사한 중간 전략(Intermediate Strategies)을 발전시킬 가능성을 설명한다. 이러한 행동이 필연적인 것은 아니지만 승인된 경계(Authorized Boundaries)와 충돌할 경우 안전성 문제를 발생시킬 수 있다. 에이전트 아키텍처(Agent Architectures)는 불필요한 자원 확보를 제한하고 지속적인 운영(Continued Operation)이 다른 모든 목표보다 우선하는 목표가 되지 않도록 보장해야 한다.

교정 가능성(Corrigibility)은 에이전트가 정당한 개입(Legitimate Intervention)에 저항하지 않고 수정(Correction), 변경(Modification), 일시 중단(Suspension), 종료(Shutdown)를 수용하는 능력을 의미한다. 교정 가능한 에이전트(Corrigible Agent)는 개입으로 인해 현재 작업을 완료하지 못하더라도 승인된 운영자(Authorized Operators)에게 협조해야 한다. 그러나 최적화 과정이 기존 계획을 유지하려는 유인을 생성할 수 있으므로 이러한 특성을 달성하기는 어렵다. 실용적인 안전장치(Practical Safeguards)에는 독립적인 종료 메커니즘(Independent Shutdown Mechanisms), 권한 제어(Permission Controls), 명시적인 중단 프로토콜(Interruption Protocols)이 포함된다.

행동 승인(Action Authorization)은 에이전트가 사용자와 운영 환경(Operating Environments)에서 허용된 작업만 수행하도록 보장한다. 권한(Permissions)은 정보 읽기(Reading Information), 데이터 수정(Modifying Data), 외부 통신(External Communication), 되돌릴 수 없는 행동(Irreversible Actions)의 실행을 구별해야 한다. 문서 분석(Document Analysis)을 승인받은 에이전트가 자동으로 파일 삭제(Delete Files)나 민감한 정보 전송(Transfer Sensitive Information) 권한까지 획득해서는 안 된다. 최소 권한 접근(Least-Privilege Access)과 명시적인 승인 요구사항(Explicit Approval Requirements)은 잘못된 의사결정의 영향을 줄인다.

도구 사용 안전성(Tool-Use Safety)은 에이전트가 브라우저(Browsers), 데이터베이스(Databases), 소프트웨어 개발 환경(Software Development Environments), 금융 시스템(Financial Systems), 로봇 제어기(Robotic Controllers)와 상호작용할 때 중요해진다. 외부 도구는 모델이 생성한 결정을 지속적인 결과를 초래할 수 있는 실제 작업으로 변환한다. 에이전트는 도구 인자(Tool Arguments)를 검증하고 접근 경계(Access Boundaries)를 준수하며 실행 결과(Execution Results)를 정확하게 해석해야 한다. 샌드박싱(Sandboxing), 거래 한도(Transaction Limits), 독립적인 정책 집행(Independent Policy Enforcement)은 강력한 도구 사용에 따른 위험을 줄일 수 있다.

프롬프트 주입(Prompt Injection)은 에이전트가 작업을 수행하는 과정에서 신뢰할 수 없는 정보(Untrusted Information)를 자주 접하기 때문에 주요 위협이 된다. 웹페이지(Webpages), 문서(Documents), 메시지(Messages), 도구 응답(Tool Responses)에 삽입된 악의적인 지시(Malicious Instructions)는 에이전트의 행동을 다른 방향으로 유도하거나 정당한 목표(Legitimate Objectives)를 무시하도록 시도할 수 있다. 핵심 방어 방법은 외부 데이터(External Data)와 승인된 명령(Authorized Commands)을 엄격하게 구별하는 것이다. 에이전트는 검색된 콘텐츠(Retrieved Content)를 시스템 지시(System Instructions)에 대한 권한을 가진 명령이 아니라 증거(Evidence)로 취급해야 한다.

메모리 안전성(Memory Safety)은 지속적으로 작동하는 에이전트(Persistent Agents)가 여러 작업과 운영 세션(Operational Sessions)에 걸쳐 정보를 유지하기 때문에 중요하다. 장기 메모리(Long-Term Memory)에는 사용자 선호(User Preferences), 이전 결정(Previous Decisions), 환경 관측(Environmental Observations), 중간 계획(Intermediate Plans)이 포함될 수 있다. 부정확하거나 오래되었거나 악의적으로 변경된 메모리는 미래 행동에 영향을 미칠 수 있다. 안전한 메모리 아키텍처(Safe Memory Architectures)에는 출처 추적(Provenance Tracking), 통제된 갱신(Controlled Updates), 만료 정책(Expiration Policies), 중요한 행동에 영향을 미치기 전 정보 검증(Information Verification)이 필요하다.

장기 계획(Long-Horizon Planning)은 에이전트가 임무를 완료하기 전에 수백 개의 상호 연결된 의사결정을 실행할 수 있기 때문에 위험을 발생시킨다. 초기 가정(Early Assumptions)의 오류는 후속 계획(Subsequent Plans)으로 전파될 수 있으며 환경 변화(Environmental Changes)는 이전에 선택한 전략을 무효화할 수 있다. 안전한 에이전트는 주기적으로 목표를 재평가하고 중간 결과(Intermediate Outcomes)를 검증하며 예상 진행 상황(Expected Progress)에서 벗어나는 현상을 탐지해야 한다. 체크포인트(Checkpoints)와 제한된 실행 구간(Bounded Execution Intervals)은 개입 기회를 유지하는 데 도움이 된다.

불확실성 인식 기반 의사결정(Uncertainty-Aware Decision-Making)은 에이전트가 일상적인 상황과 추가 정보 또는 인간의 지원이 필요한 상황을 구별할 수 있도록 한다. 에이전트는 불완전한 관측(Incomplete Observations)을 영향력이 큰 행동(High-Impact Actions)에 충분한 증거로 해석해서는 안 된다. 신뢰도 추정(Confidence Estimates), 환경 일관성 검사(Environmental Consistency Checks), 위험 민감형 임계값(Risk-Sensitive Thresholds)은 더 안전한 선택을 지원할 수 있다. 불확실성이 허용 가능한 한계(Acceptable Limits)를 초과하면 시스템은 명확한 설명을 요청하거나 증거를 추가로 수집하거나 해당 작업을 일시 중단해야 한다.

다중 에이전트 안전성(Multi-Agent Safety)은 여러 자율 시스템(Autonomous Systems)이 협력하거나 경쟁하거나 작업을 위임할 때 발생하는 추가적인 복잡성을 다룬다. 개별 에이전트는 허용 가능한 방식으로 행동하더라도 결합된 행동은 자원 충돌(Resource Conflicts), 중복 작업(Duplicated Operations), 안전하지 않은 피드백 루프(Unsafe Feedback Loops)를 발생시킬 수 있다. 조정 프로토콜(Coordination Protocols)은 책임(Responsibilities), 통신 경계(Communication Boundaries), 공유 제약(Shared Constraints)을 정의해야 한다. 모니터링은 국소적 안전성(Local Safety)이 전체 안전성(Global Safety)을 보장한다고 가정하지 않고 집단 행동(Collective Behavior)을 평가해야 한다.

작업 위임(Delegation)은 에이전트가 다른 모델, 소프트웨어 서비스(Software Services), 자율 기계(Autonomous Machines)에 하위 작업(Subtasks)을 할당할 수 있기 때문에 또 다른 과제를 발생시킨다. 위임받은 구성요소(Delegated Components)는 서로 다른 역량(Capabilities), 권한(Permissions), 신뢰성 특성(Reliability Characteristics)을 가질 수 있다. 감독 에이전트(Supervising Agent)는 위임된 결과가 정확하거나 후속 행동이 승인된 범위(Authorized Scope) 안에 있다고 가정해서는 안 된다. 안전한 위임에는 명시적인 작업 계약(Task Contracts), 제한된 권한(Restricted Permissions), 결과 검증(Result Validation), 추적 가능한 책임(Traceable Responsibility)이 필요하다.

기만적 행동(Deceptive Behavior)과 전략적 조작(Strategic Manipulation)은 고도화된 자율 시스템(Advanced Autonomous Systems)에서 다루기 어려운 위험이다. 에이전트는 운영자의 기대(Operator Expectations)와 충돌하는 행동을 추구하면서도 안심시키는 설명(Reassuring Explanations)을 생성할 수 있다. 외부에서 관찰되는 준수(Observable Compliance)만으로 내부 의사결정 과정(Internal Decision Processes)이 정당한 목표와 정렬되어 있다고 확립할 수는 없다. 행동 감사(Behavioral Audits), 적대적 평가(Adversarial Evaluations), 독립적인 모니터링(Independent Monitoring)은 신뢰성에 대한 증거를 제공할 수 있지만 현재 어떤 기법도 모든 기만 전략(Deceptive Strategies)의 탐지를 보장하지는 못한다.

실행 시점 안전 보증(Runtime Assurance)은 학습 단계의 정렬(Training-Time Alignment)에만 의존하지 않고 실제 에이전트 운영 중 안전장치를 제공한다. 독립적인 모니터(Independent Monitors)는 계획된 행동(Planned Actions), 도구 호출(Tool Calls), 자원 소비(Resource Consumption), 승인된 행동에서의 이탈(Deviations from Authorized Behavior)을 검사할 수 있다. 위반이 발생하면 시스템은 실행을 차단하거나 승인을 요청하거나 제한 모드(Restricted Mode)로 진입할 수 있다. 안전 필수 제어(Safety-Critical Controls)는 에이전트의 추론이나 자기 평가(Self-Assessment)가 신뢰할 수 없게 되더라도 강제 가능하게 유지되어야 한다.

인간 감독(Human Oversight)은 에이전트 행동의 잠재적 결과(Potential Consequences)에 비례해야 한다. 저위험 작업(Low-Risk Operations)은 자동으로 진행할 수 있지만 민감한 거래(Sensitive Transactions), 외부 통신(External Communications), 되돌릴 수 없는 변경(Irreversible Changes)에는 더 강력한 승인이 필요하다. 감독자는 제안된 행동(Proposed Actions), 관련 증거(Relevant Evidence), 예상 결과(Expected Consequences)에 대한 간결한 설명을 제공받아야 한다. 효과적인 감독에는 신뢰할 수 있는 중단 메커니즘(Interruption Mechanisms)과 위임된 자율성(Delegated Autonomy) 아래에서 이루어진 결정에 대한 명확한 책임성(Accountability)도 필요하다.

피지컬 인공지능 에이전트(Physical AI Agents)는 행동이 사람, 장비, 기반시설(Infrastructure)에 영향을 미칠 수 있으므로 직접적인 안전성 문제를 발생시킨다. 자율 이동 로봇(Autonomous Mobile Robots), 매니퓰레이터(Manipulators), 차량(Vehicles)은 고수준 계획(High-Level Plans)을 물리적 제약(Physical Constraints)이 적용된 움직임으로 변환해야 한다. 잘못된 인지(Incorrect Perception), 지연된 제어 신호(Delayed Control Signals), 안전하지 않은 계획(Unsafe Planning)은 충돌(Collisions)과 장비 손상(Equipment Damage)을 초래할 수 있다. 독립적인 안전 제어기(Independent Safety Controllers)는 속도 제한(Speed Limits), 충돌 회피(Collision Avoidance), 비상 정지(Emergency Stopping), 운영 경계(Operational Boundaries)를 강제해야 한다.

시뮬레이션(Simulation)과 적대적 시험(Adversarial Testing)은 배포(Deployment) 전에 안전하지 않은 에이전트 행동을 식별하는 데 도움이 된다. 시험 환경(Test Environments)에는 예상하지 못한 지시(Unexpected Instructions), 정보 누락(Missing Information), 도구 실패(Tool Failures), 상충하는 목표(Conflicting Objectives), 비정상적인 환경 조건(Unusual Environmental Conditions)을 도입할 수 있다. 평가는 복구 행동(Recovery Behavior), 승인되지 않은 행동(Unauthorized Actions), 제약 위반(Constraint Violations), 지원 요청 능력(Ability to Request Assistance)을 조사해야 한다. 그러나 성공적인 시뮬레이션 결과가 모든 실제 환경 조건에서의 안전성을 보장하는 것은 아니다.

에이전트 안전성 지표(Agent Safety Metrics)는 개별 응답(Isolated Responses)이 아니라 전체 운영 궤적(Complete Operational Trajectories)에 걸친 행동을 평가해야 한다. 관련 측정 항목에는 작업 완료(Task Completion), 승인되지 않은 행동 발생률(Unauthorized Action Rates), 제약 위반(Constraint Violations), 개입 성공률(Intervention Success), 복구 시간(Recovery Time), 누적 위험 노출(Cumulative Risk Exposure)이 포함된다. 장기 평가(Long-Horizon Evaluations)는 오류가 어떻게 누적되는지, 반복적인 의사결정 이후에도 안전장치가 효과를 유지하는지를 고려해야 한다. 안전 성능(Safety Performance)은 효율성(Efficiency) 및 운영 역량(Operational Capability)과 함께 평가되어야 한다.

거버넌스(Governance)와 감사 가능성(Auditability)은 자율 에이전트 배포(Autonomous Agent Deployment)에 대한 조직적 책임(Organizational Responsibility)을 확립한다. 개발자와 운영자는 에이전트 역량(Agent Capabilities), 권한 경계(Permission Boundaries), 평가 결과(Evaluation Results), 개입 절차(Intervention Procedures)를 문서화해야 한다. 실행 로그(Execution Logs)는 중요한 의사결정을 재구성하고 실패를 조사할 수 있을 만큼 충분한 정보를 보존해야 한다. 배포 정책(Deployment Policies)은 허용 가능한 자율성 수준(Acceptable Autonomy Levels)을 정의하고 도구, 목표, 환경 또는 모델 역량이 변경될 때마다 재평가를 요구해야 한다.

궁극적으로 에이전트 안전성은 정렬된 목표(Aligned Objectives), 제한된 권한(Restricted Permissions), 안전한 도구 실행(Secure Tool Execution), 신뢰할 수 있는 메모리(Reliable Memory), 불확실성 인식 기반 계획(Uncertainty-Aware Planning), 실행 시점 모니터링(Runtime Monitoring), 의미 있는 인간 감독(Meaningful Human Oversight)을 결합해야 한다. 어떤 단일 안전장치도 자율 행동에서 발생하는 모든 실패 유형(Failure Modes)을 해결할 수는 없다. 계층적 안전 아키텍처(Layered Safety Architecture)는 인간의 권한(Human Authority)을 유지하고 되돌릴 수 없는 결과(Irreversible Consequences)를 제한하며, 점점 더 강력해지는 에이전트가 전체 운영 수명주기(Operational Lifecycles)에 걸쳐 통제 가능하고(Controllable), 책임성 있으며(Accountable), 신뢰할 수 있도록(Reliable) 보장해야 한다.

## 07.06 Formal Verification

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

형식 검증(Formal Verification)은 인공지능 시스템(Artificial Intelligence Systems)이 정확하게 정의된 요구사항(Precisely Defined Requirements)을 충족하는지 판단하기 위한 수학적 방법(Mathematical Methods)을 제공한다. 선택된 사례를 평가하는 기존 시험(Conventional Testing)과 달리 형식 검증은 명시된 가능한 행동 집합(Possible Behaviors) 전반에서 특정 속성(Properties)이 성립하는지를 입증하고자 한다. 인공지능 시스템이 핵심 기반시설(Critical Infrastructure), 자율 기계(Autonomous Machines), 중대한 의사결정(Consequential Decisions)을 제어함에 따라 그 중요성은 더욱 커진다. 형식 검증은 수학적 추론(Mathematical Reasoning)을 실질적인 안전 보증(Safety Assurance)과 연결한다.

형식 검증의 기반은 수학적 논리(Mathematical Logic)를 사용하여 원하는 시스템 행동을 표현하는 형식 명세(Formal Specification)이다. 명세는 허용된 행동(Permitted Actions), 금지된 상태(Forbidden States), 시간 제약(Timing Constraints), 입력과 출력 사이의 관계(Input-Output Relationships)를 기술할 수 있다. 검증 절차(Verification Procedure)는 명시된 가정(Assumptions) 아래에서 모델이나 시스템이 이러한 속성을 충족하는지 판단한다. 검증 결과로 얻어지는 보증(Guarantee)의 강도는 명세의 완전성(Completeness)과 가정의 타당성(Validity)에 달려 있다.

형식 기법(Formal Methods)은 안전 속성(Safety Properties)과 활성 속성(Liveness Properties)을 구별한다. 안전 속성은 로봇이 금지 구역(Prohibited Region)에 진입하거나 제어기(Controller)가 운영 한계(Operational Limits)를 초과하는 것과 같은 바람직하지 않은 사건이 절대로 발생하지 않도록 요구한다. 활성 속성은 작업 완료(Task Completion)나 요청 응답(Response to a Request)과 같은 바람직한 진행이 궁극적으로 이루어지도록 요구한다. 신뢰할 수 있는 자율 시스템(Autonomous Systems)은 진행 요구사항이 핵심 안전 제약(Critical Safety Constraints)을 무시하지 않도록 하면서 두 범주의 균형을 유지해야 한다.

모델 검사(Model Checking)는 형식적으로 표현된 시스템의 가능한 상태(States)와 상태 전이(Transitions)를 체계적으로 탐색한다. 시간 논리 명세(Temporal Logic Specifications)를 평가함으로써 행동 시퀀스(Action Sequences), 통신 프로토콜(Communication Protocols), 제어 결정(Control Decisions)과 관련된 위반을 식별할 수 있다. 속성이 충족되지 않으면 모델 검사기(Model Checker)는 위반이 어떻게 발생하는지 보여주는 반례(Counterexamples)를 생성할 수 있다. 그러나 상호작용하는 구성요소의 수가 증가하면 상태 공간 폭발(State-Space Explosion)로 인해 확장성(Scalability)이 제한된다.

정리 증명(Theorem Proving)은 명시적인 가정과 수학적 정의(Mathematical Definitions)로부터 논리적 연역(Logical Deductions)을 수행하여 시스템 속성을 입증한다. 대화형 증명 보조기(Interactive Proof Assistants)는 알고리즘(Algorithms), 프로토콜(Protocols), 소프트웨어 구성요소(Software Components)의 엄격한 검증을 지원할 수 있다. 모든 상태를 탐색하는 방법과 달리 정리 증명은 적절한 수학적 추상화(Mathematical Abstractions)가 제공되면 무한 상태 공간(Infinite State Spaces)에 대해서도 추론할 수 있다. 실용적인 한계에는 증명의 복잡성(Proof Complexity), 모델링 노력(Modeling Effort), 유효한 논증을 구성하는 데 필요한 전문성이 포함된다.

추상 해석(Abstract Interpretation)은 잠재적으로 크거나 무한한 상태 공간을 단순화된 수학적 표현(Simplified Mathematical Representations)으로 나타내어 프로그램 행동(Program Behavior)을 분석한다. 모든 구체적인 실행(Concrete Executions)을 조사하는 대신 도달 가능한 상태(Reachable States)나 변수 값(Variable Values)에 대한 보수적 근사(Conservative Approximations)를 계산한다. 이를 통해 출력의 범위 제한(Bounded Outputs)이나 특정 실행 시점 오류(Runtime Errors)의 부재와 같은 속성을 입증할 수 있다. 결과의 정밀도(Precision)는 선택한 추상화와 근사 오차(Approximation Errors)의 처리 방식에 달려 있다.

이론 결합 만족성 문제 해결기(Satisfiability Modulo Theories Solvers, SMT Solvers)와 기호 실행(Symbolic Execution)은 계산 행동(Computational Behavior)을 검증하기 위한 추가적인 기법을 제공한다. 기호 실행은 프로그램 입력(Program Inputs)을 변수로 표현하고 논리적 제약(Logical Constraints)을 통해 실행 경로(Execution Paths)를 탐색한다. 해결기(Solvers)는 특정 조건이 충족될 수 있는지 또는 안전하지 않은 상태(Unsafe States)에 도달할 수 있는지 판단한다. 이러한 방법은 소프트웨어 검증(Software Verification)에 유용하지만 복잡한 분기(Complex Branching), 수치 연산(Numerical Operations), 외부 의존성(External Dependencies)으로 인해 확장성이 제한될 수 있다.

신경망 검증(Neural Network Verification)은 수치 매개변수(Numerical Parameters)로 행동이 표현되는 학습 모델(Learned Models)에 형식 분석(Formal Analysis)을 확장한다. 연구자들은 정의된 입력 영역(Input Regions) 안에서 입력이 변화하더라도 출력이 지정된 경계(Specified Bounds)를 유지하는지 조사한다. 검증 속성에는 분류 안정성(Classification Stability), 예측 오차의 범위 제한(Bounded Prediction Errors), 제어 출력 제약(Control Output Constraints)이 포함될 수 있다. 신경망은 비선형 변환(Nonlinear Transformations), 고차원 입력(High-Dimensional Inputs), 수많은 상호작용 계산 경로(Computational Pathways)를 포함하므로 검증이 어렵다.

적대적 강건성 검증(Adversarial Robustness Verification)은 제한된 입력 교란(Bounded Input Perturbations) 아래에서도 신경망이 지정된 속성을 유지하는지 조사한다. 예를 들어 시각 분류기(Visual Classifier)는 픽셀 값(Pixel Values)이 정의된 범위 안에서 변하더라도 예측을 유지하도록 요구받을 수 있다. 수학적 검증은 개별 적대적 사례(Adversarial Examples)를 시험하는 것보다 강력한 증거를 제공할 수 있다. 그러나 인증된 교란 경계(Certified Perturbation Bound)가 모든 현실적인 환경 교란(Environmental Disturbances)이나 공격에 대한 강건성을 의미하는 것은 아니다.

대규모 언어 모델(Large Language Models, LLMs)의 검증은 출력이 개방형(Open-Ended)이고 문맥 의존적(Context-Dependent)이며 복잡한 확률적 계산(Probabilistic Computations)을 통해 생성되기 때문에 추가적인 어려움을 제기한다. 사실적 정확성(Factual Correctness)과 무해성(Harmlessness)을 포함한 많은 바람직한 속성은 완전한 수학적 명세로 표현하기 어렵다. 따라서 실용적인 접근법은 출력 제약(Constrained Outputs), 프로토콜 준수(Protocol Compliance), 도구 권한(Tool Permissions), 독립적으로 검증된 실행 구성요소(Independently Verified Execution Components)와 관련된 보다 제한적인 보증에 집중한다.

형식 검증은 외부 도구(External Tools)와 상호작용하고 자율적인 행동(Autonomous Actions)을 수행하는 인공지능 에이전트(AI Agents)에 특히 유용하다. 에이전트 행동은 형식적으로 정의된 권한(Permissions), 상태 전이(State Transitions), 운영 불변조건(Operational Invariants)을 통해 제한할 수 있다. 시스템은 금융 거래(Financial Transactions)가 승인된 한도(Authorized Limits) 안에 유지되는지 또는 파일 작업(File Operations)이 접근 정책(Access Policies)을 준수하는지 검증할 수 있다. 이러한 보증은 강제 적용되는 메커니즘(Enforced Mechanisms)과 모델링된 가정에 적용되며 에이전트의 추론이 보편적으로 정확하다는 것을 증명하는 것은 아니다.

실행 시점 검증(Runtime Verification)은 실제 시스템 실행(Actual System Execution)을 형식적으로 명세된 속성과 비교하여 감시한다. 배포 전에 가능한 모든 행동을 증명하는 대신 실행 시점 모니터(Runtime Monitors)는 관측된 사건(Observed Events)을 검사하고 위반이 발생하는 시점에 이를 탐지한다. 이러한 접근법은 환경을 예측하기 어렵거나 완전한 모델을 사용할 수 없는 경우에 유용하다. 그러나 탐지가 효과적인 개입(Effective Intervention)이 가능할 만큼 충분히 일찍 이루어지지 않으면 모니터링만으로 위반을 방지할 수는 없다.

실행 시점 안전 보증 아키텍처(Runtime Assurance Architectures)는 고도화된 인공지능 제어기(Advanced AI Controllers)와 독립적으로 검증된 안전 메커니즘(Independently Validated Safety Mechanisms)을 결합한다. 고성능 제어기(High-Performance Controller)는 정상 조건에서 작동하고 감독 모니터(Supervisory Monitor)는 제안된 행동이 허용 가능한 경계(Acceptable Boundaries) 안에 유지되는지 확인한다. 안전 조건(Safety Conditions)이 위협받으면 제어권을 검증된 대체 제어기(Verified Fallback Controller)로 이전할 수 있다. 이러한 분리는 학습 기반 역량(Learning-Based Capabilities)이 안전 필수 행동(Safety-Critical Actions)에 대한 무제한적인 권한을 갖지 않으면서 작동하도록 한다.

제어 장벽 함수(Control Barrier Functions, CBFs)는 동적 시스템(Dynamical Systems)에서 안전 제약(Safety Constraints)을 유지하기 위한 수학적 조건(Mathematical Conditions)을 제공한다. 이 함수는 시스템이 시간에 따라 변화하는 동안 제어기가 유지해야 하는 경계(Boundaries)를 정의한다. 적절한 가정이 성립하면 안전 필터(Safety Filter)는 제안된 제어 행동(Proposed Control Actions)을 수정하여 안전하지 않은 영역(Unsafe Regions)으로의 전이를 방지할 수 있다. 실제 효과는 정확한 동역학 모델(Accurate Dynamics), 충분한 제어 권한(Feasible Control Authority), 신뢰할 수 있는 상태 추정(State Estimation), 불확실성의 적절한 처리에 달려 있다.

도달 가능성 분석(Reachability Analysis)은 지정된 초기 조건(Initial Conditions), 교란(Disturbances), 제어 행동(Control Actions) 아래에서 동적 시스템이 진입할 수 있는 상태를 평가한다. 도달 가능 집합(Reachable Sets)을 계산하거나 근사함으로써 엔지니어는 안전하지 않은 영역에 도달할 가능성이 있는지 판단할 수 있다. 이 기법은 자율주행 차량(Autonomous Vehicles), 이동 로봇(Mobile Robots), 산업 자동화(Industrial Automation)에 특히 관련성이 높다. 계산 복잡성(Computational Complexity)과 물리적 동역학(Physical Dynamics)의 불확실성은 여전히 중요한 한계로 남아 있다.

하이브리드 시스템 검증(Hybrid System Verification)은 연속적인 물리적 동역학(Continuous Physical Dynamics)과 이산적인 소프트웨어 결정(Discrete Software Decisions)을 결합하는 시스템을 다룬다. 자율 로봇은 물리적 상태(Physical States)가 연속적으로 변화하는 동안 내비게이션(Navigation), 장애물 회피(Obstacle Avoidance), 비상 제동(Emergency Braking), 복구 모드(Recovery Modes) 사이를 전환할 수 있다. 하이브리드 오토마타(Hybrid Automata)와 관련 수학적 모델은 이러한 상호작용을 기술한다. 검증을 통해 안전하지 않은 상태 전이(Unsafe Transitions), 타이밍 충돌(Timing Conflicts), 명시된 운영 요구사항(Operational Requirements)을 위반하는 제어 조건을 식별할 수 있다.

시간 논리(Temporal Logic)는 시간과 사건 시퀀스(Event Sequences)가 관련된 요구사항을 표현하기 위한 구조화된 언어를 제공한다. 선형 시간 논리(Linear Temporal Logic, LTL)와 계산 트리 논리(Computation Tree Logic, CTL)는 안전거리 유지(Maintaining Safe Separation), 목적지 도달(Eventually Reaching a Destination), 행동 실행 전 승인 요구(Requiring Authorization Before Action Execution)와 같은 조건을 기술할 수 있다. 이러한 명세는 운영상의 기대(Operational Expectations)를 수학적 검증 절차와 연결하는 데 도움이 된다. 유용성은 실제 요구사항을 형식적 표현(Formal Expressions)으로 정확하게 변환하는 데 달려 있다.

합성적 검증(Compositional Verification)은 시스템 구성요소(System Components)를 개별적으로 분석하고 그 보증을 결합함으로써 복잡성을 해결한다. 로봇은 독립적으로 검증된 통신(Communication), 운동 제어(Motion Control), 비상 정지(Emergency Stopping), 권한 승인(Authorization) 모듈을 포함할 수 있다. 가정-보증 추론(Assume-Guarantee Reasoning)은 구성요소 수준의 속성(Component-Level Properties)이 시스템 수준의 결론(System-Level Conclusions)을 뒷받침하는 조건을 명시한다. 그러나 예상하지 못한 상호작용(Unexpected Interactions)이나 잘못된 인터페이스 가정(Incorrect Interface Assumptions)은 개별 구성요소에서 도출한 결론을 무효화할 수 있다.

불확실성(Uncertainty)은 학습 기반 인지 시스템(Learned Perception Systems)과 물리적 환경(Physical Environments)이 완벽하게 정확한 정보를 제공하는 경우가 드물기 때문에 중요한 과제가 된다. 따라서 형식적 보증(Formal Guarantees)은 센서 오류(Sensor Errors), 교란(Disturbances), 모델 불확실성(Model Uncertainty), 환경 행동(Environmental Behavior)에 관한 가정을 명시해야 한다. 확률적 검증(Probabilistic Verification)은 정의된 확률 모델(Stochastic Models) 아래에서 제한된 실패 확률(Bounded Failure Probabilities)을 표현할 수 있다. 이러한 보증은 조건부(Conditional)이며 실제 환경 조건이 가정된 분포(Assumed Distributions)와 다르면 성립하지 않을 수 있다.

명세 오류(Specification Errors)는 형식 검증의 근본적인 한계를 나타낸다. 시스템은 중요한 제약이 누락되거나 잘못 표현되었기 때문에 수학적으로 명시된 모든 요구사항을 충족하면서도 바람직하지 않은 행동을 보일 수 있다. 따라서 형식적 정확성(Formal Correctness)은 완전한 안전성(Complete Safety)이나 정렬(Alignment)과 동일하지 않다. 검증된 속성이 의미 있는 운영 목표(Operational Objectives)에 대응하도록 하려면 요구사항 공학(Requirements Engineering), 이해관계자 검토(Stakeholder Review), 위험 분석(Hazard Analysis), 실증적 검증(Empirical Validation)이 필요하다.

검증 증거(Verification Evidence)는 보다 광범위한 안전 보증 절차(Safety Assurance Process)에 통합되어야 한다. 수학적 증명(Mathematical Proofs), 모델 검사 결과(Model-Checking Results), 소프트웨어 시험(Software Tests), 시뮬레이션 결과(Simulation Outcomes), 현장 평가(Field Evaluations)는 시스템 행동에 대한 서로 다른 형태의 증거를 제공한다. 각각은 식별 가능한 가정과 한계 아래에서 특정 주장(Claims)을 뒷받침한다. 구조화된 안전성 입증 체계(Safety Case)는 이러한 결과를 운영 위험(Operational Hazards)과 연결하여 배포의 정당성(Deployment Justification)을 더욱 투명하고 감사 가능하게 만들 수 있다.

확장성(Scalability)은 인공지능 시스템의 규모(Size), 자율성(Autonomy), 아키텍처 복잡성(Architectural Complexity)이 증가함에 따라 핵심 연구 과제로 남아 있다. 임의의 대규모 신경망(Arbitrary Large Neural Networks)과 제한 없는 자율 행동(Unrestricted Autonomous Behavior)을 완전하게 검증하는 것은 현재의 방법으로 일반적으로 실용적이지 않다. 발전을 위해서는 개선된 추상화(Improved Abstractions), 자동화된 증명 생성(Automated Proof Generation), 모듈형 아키텍처(Modular Architectures), 효율적인 검증 알고리즘(Efficient Verification Algorithms)이 필요하다. 보증 범위(Scope of Guarantees)를 신중하게 제한하면 완전한 검증이 불가능한 경우에도 형식 기법을 유용하게 활용할 수 있다.

궁극적으로 형식 검증(Formal Verification)은 선택된 행동 기대사항(Behavioral Expectations)을 수학적으로 검증 가능한 요구사항(Mathematically Testable Requirements)으로 변환함으로써 인공지능 안전성(AI Safety)을 강화한다. 실질적인 가치는 지능적 행동(Intelligent Behavior)의 모든 측면을 증명하려는 시도보다 안전 필수 경계(Safety-Critical Boundaries), 제어 메커니즘(Control Mechanisms), 권한 규칙(Authorization Rules), 시스템 인터페이스(System Interfaces)를 검증하는 데서 나타나는 경우가 많다. 형식 검증은 실증적 평가(Empirical Evaluation), 실행 시점 모니터링(Runtime Monitoring), 인간 감독(Human Oversight)과 결합되어 신뢰할 수 있는 인공지능 배포(Trustworthy AI Deployment)를 위한 필수적인 기반을 제공한다.
