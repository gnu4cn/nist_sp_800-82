# 定制注意事项

这一出版物中的 OT 叠加层，利用了 NIST SP 800-53B 的控制基线，该基线考虑了 OT 系统的独特特征，例如对可用性、安全性，以及环境或运营环境考虑因素的日益增长的需求。此外，OT 系统的架构和技术选择差异很大。 NIST SP 800-53B 控制基线是根据这些一般考虑因素量身定制的，包括添加与 OT 环境相关的控制措施。组织可以使用这一叠加层作为起点，并进一步定制控制措施，以满足特定的运营需求，从而满足 OT 系统的可变性。

随着组织进一步定制控制措施，以满足其内部安全要求，限制（例如技术、操作限制、环境考虑等）可能就需要选择补偿性控制措施。当 OT 无法支持某些控制措施，或控制增强时，或者当组织由于对性能、安全性或可靠性的潜在不利影响，而确定不建议实施控制或控制增强时，可能需要在 OT 环境中进行补偿控制措施，compensating controls。所谓补偿控制措施，是特定于基线控制措施或增强的替代方案，可提供同等或相当的保护。例如，当控制措施或控制增强需要自动化机制，而这些机制在 OT 环境中不易获得、不具有成本效益或技术上不可行时，则可以接受通过非自动化机制或程序(procedures)实施的补偿控制来满足控制的意图。

根据 SP 800-53 第 5 版的 PL-11 实施的补偿控制措施，不被视为基线控制的例外或豁免。相反，他们属于 OT 环境中采用的替代保障措施和对策，可实现那些无法有效采用的原始控制的目的。请参阅 NIST SP 800-37 第 2 版 【[SP800-37r2](../refs.md#sp800-37r2)】 第 3.3 小节中的 “控制定制”。

使用补偿控制措施还可以包括补充基线的控制增强。使用补偿控制措施，通常涉及额外风险和减少功能之间的权衡。补偿控制措施的每次使用，都应基于风险来确定接受多少残余风险，以及减少多少功能。此外，在采用补偿控制措施时，组织应记录理由并描述：

- 为什么无法实施基线控制；
- 补偿控制如何为 OT 系统提供同等的安全功能；
- 对因使用补偿控制而不是基线控制，而产生的任何残余风险的风险接受程度。


关于使用补偿控制措施的组织决策，要记录在 OT 的安全计划中。

包含分配的控制措施（例如，*分配：组织定义的条件或触发事件*），可以根据基线进行定制。这相当于分配值 “none”。对于不同的影响基线，分配可能采用不同的值。


As organizations further tailor controls to meet their internal security requirements, limitations (e.g., technology, operational constraints, environmental considerations) may necessitate the selection of compensating controls. Compensating controls in the OT environment may be required when the OT cannot support certain controls or control enhancements or when the organization determines that it is not advisable to implement controls or control enhancements due to potential adverse impacts to performance, safety, or reliability. Compensating controls are alternatives to a specific baseline control or enhancement that provides equivalent or comparable protection. For example, if controls or control enhancements require automated mechanisms that are not readily available, cost-effective, or technically feasible in OT environments, compensating controls implemented through nonautomated mechanisms or procedures may be acceptable to meet the intent of the control.
