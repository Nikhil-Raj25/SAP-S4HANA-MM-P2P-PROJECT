# SAP S/4HANA MM - P2P Cycle Hands-On Practice Project | Training System Simulation

**System:** SAP S/4HANA Training System (Practice / Simulation)

### Overview
Hands-on simulation of end-to-end Procure to Pay (P2P) cycle for raw material procurement, practiced on S/4HANA training server.

### 1. Business Scenario (Assumed for Practice)
Company Code: 1000 | Plant: 1000 | Storage: 1001 | Material Type: ROH

### 2. Master Data Created (Hands-On)
- Material Master: MM01 / MM02 - ROH, HALB, FERT
- Vendor Master: BP - Role FLVN01
- Info Record: ME11
- Source List: ME01

### 3. P2P Flow Practiced (End-to-End Simulation)
| Step | Process | T-Code | Document / Status |
| :--- | :--- | :--- | :--- |
| 1 | Purchase Requisition | ME51N | Created (PR) |
| 2 | RFQ & Quotation | ME41 / ME47 | Done |
| 3 | Price Comparison | ME49 | Done |
| 4 | Purchase Order | ME21N | PO Created |
| 5 | PO Release (Demo) | ME29N | Done |
| 6 | Goods Receipt (GR) | MIGO | GR Doc 101 Movement |
| 7 | Stock Check | MMBE / MB52 | Verified |
| 8 | Invoice Verification | MIRO | Invoice Posted |
| 9 | Payment Process Understanding | F-53 / F110 | Concept Cleared |

### 4. Inventory Management Practiced
- Movement Types: 101, 102, 122, 261, 262, 311, 321
- Stock Transport Order (STO) & Physical Inventory: MI01, MI04, MI07

### 5. Key SAP Tables Studied
EKKO, EKPO, MKPF, MSEG, RBKP, BSIM, BSEG

### 6. Common Errors Faced & Solved During Practice
- M7001 Material not in plant - Solved by extending material to plant
- OBYC Account determination missing - Understood config
- Price variance in MIRO - Learned handling

### Skills Covered
SAP MM, S/4HANA, P2P Cycle, Material Master, Vendor Master, ME21N, MIGO, MIRO, MB52, Inventory Management
