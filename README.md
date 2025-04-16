```mermaid
graph TD
    classDef gov fill:#4CAF50,stroke:#388E3C,color:white;
    classDef company fill:#2196F3,stroke:#1976D2,color:white;
    classDef tech fill:#FF9800,stroke:#F57C00;
    classDef ops fill:#9C27B0,stroke:#7B1FA2,color:white;
    classDef third fill:#E91E63,stroke:#C2185B,color:white;
    classDef exchange fill:#009688,stroke:#00796B,color:white;
    classDef bank fill:#607D8B,stroke:#455A64,color:white;

    A[政府机构] -->|提供公共数据| B[城投公司]
    B -->|签订数据服务协议| C[滨智集团/智慧集团]
    C --> C1[数据脱敏加密]
    C --> C2[数据资产确权]
    C --> C3[技术处理\n（区块链存证）]
    C1 & C2 & C3 --> D[形成数据资产包]
    D -->|签订运营协议| E[智慧集团] 🌟修改处
    E -->|签订运营协议| F[第三方专业机构] 🌟关联节点同步生效
    F --> F1[政务应用场景开发\n（智慧交通）]
    F --> F2[商业应用场景开发\n（精准营销）]
    F --> F3[科研应用场景开发\n（城市建模）]
    F1 & F2 & F3 --> G[北方大数据交易所]
    G --> G1[数据产品挂牌]
    G --> G2[合规交易撮合]
    G --> G3[收益清算分配]
    G1 & G2 & G3 --> H[收入回款]
    H --> B
    B -->|质押/ABS融资| I[商业银行]

    class A gov
    class B,C,D,E company  🌟保持原有样式不变
    class C1,C2,C3 tech
    class F,F1,F2,F3 third
    class G,G1,G2,G3 exchange
    class I bank
