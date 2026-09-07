# SAP S/4HANA MM - P2P Cycle Implementation (Fresher Project)

**Author:** Nikhil Raj | MCA | SAP MM Trained | Pune / Bangalore | Immediate Joiner
**System:** SAP S/4HANA Training System

### Overview
End-to-end Procure to Pay (P2P) cycle for raw material procurement.

### 1. Business Scenario
Company Code: 1000 | Plant: 1000 | Storage: 1001 | Material Type: ROH

### 2. Master Data Created
- Material Master: MM01 / MM02 - ROH, HALB, FERT
- Vendor Master: BP - Role FLVN01
- Info Record: ME11
- Source List: ME01

### 3. P2P Flow Practiced (End-to-End)
| Step | Process | T-Code | Status |
| :--- | :--- | :--- | :--- |
| 1 | Purchase Requisition | ME51N | Created |
| 2 | RFQ & Quotation | ME41 / ME47 | Done |
| 3 | Price Comparison | ME49 | Done |
| 4 | Purchase Order | ME21N | PO 4500007891 |
| 5 | PO Release | ME29N | Done |
| 6 | Goods Receipt | MIGO | Doc 5000012345 (101) |
| 7 | Stock Check | MMBE / MB52 | Verified |
| 8 | Invoice Verification | MIRO | Doc 5100001234 |
| 9 | Payment | F-53 | Cleared |

### 4. Inventory Management
- Movement Types: 101, 102, 122, 261, 262, 311, 321
- STO, Physical Inventory: MI01, MI04, MI07

### 5. Key Tables
EKKO, EKPO, MKPF, MSEG, RBKP, BSIM, BSEG

### 6. Errors Solved
- M7001 Material not in plant - Solved by extending material
- OBYC Account determination - Solved by config
- Price variance in MIRO - Solved

### 7. Result
Full P2P cycle completed with stock update and accounting entries (BSX, WRX, GR/IR).

### Skills
SAP MM, S/4HANA, P2P, MIGO, MIRO, ME21N, Material Master, Vendor Master

---
**Open for:** SAP MM Consultant - Pune / Bangalore - Immediate Joiner
