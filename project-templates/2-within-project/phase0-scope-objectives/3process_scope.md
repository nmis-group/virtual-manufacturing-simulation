# 3. Process Scope

## 3.1 Scope of Simulation Model

| Scope Element | Description | Boundaries | In Scope | Out of Scope |
|---------------|-------------|------------|----------|--------------|
| **Start Point** | Where the simulation begins | | ✓ | |
| **End Point** | Where the simulation concludes | | ✓ | |
| **Specific Processes Included** | Manufacturing processes to model | | | |
| **Systems & Components** | Equipment and resources included | | | |
| **Geographic Boundaries** | Physical locations covered | | | |
| **Time Horizon** | Temporal scope of analysis | | | |

## 3.2 Process Boundaries

### Manufacturing Process Flow
```
[Supplier] → [Receiving] → [Storage] → [Production] → [Quality Control] → [Packaging] → [Shipping] → [Customer]
     ↑              ↑           ↑            ↑              ↑              ↑             ↑
   Out of      In Scope    In Scope    In Scope      In Scope      In Scope    Out of
   Scope                                                                        Scope
```

### Detailed Scope Definition

#### **Included in Model:**
- [ ] Raw material receiving and inspection
- [ ] Inventory management and storage
- [ ] Primary production processes
- [ ] Quality control and testing
- [ ] Packaging and finishing operations
- [ ] Equipment maintenance activities
- [ ] Shift patterns and staffing
- [ ] Material handling and transportation

#### **Excluded from Model:**
- [ ] Supplier delivery logistics
- [ ] Customer distribution and shipping
- [ ] Financial and accounting processes
- [ ] Human resource management
- [ ] Strategic planning activities
- [ ] Marketing and sales operations
- [ ] External supply chain partners

## 3.3 Physical Boundaries

### Production Area Layout
| Area/Zone | Equipment/Resources | Included | Justification |
|-----------|-------------------|----------|---------------|
| **Receiving Dock** | Goods-in processing | [ ] Yes [ ] No | |
| **Raw Material Storage** | Warehouse operations | [ ] Yes [ ] No | |
| **Production Line 1** | Primary manufacturing | [ ] Yes [ ] No | |
| **Production Line 2** | Secondary manufacturing | [ ] Yes [ ] No | |
| **Quality Laboratory** | Testing and inspection | [ ] Yes [ ] No | |
| **Packaging Area** | Finishing operations | [ ] Yes [ ] No | |
| **Finished Goods Storage** | Warehouse operations | [ ] Yes [ ] No | |
| **Shipping Dock** | Goods-out processing | [ ] Yes [ ] No | |
| **Maintenance Workshop** | Equipment service | [ ] Yes [ ] No | |
| **Utilities** | Power, water, compressed air | [ ] Yes [ ] No | |

## 3.4 Process Detail Mapping

### Core Manufacturing Processes

#### Process 1: [Process Name]
- **Start Trigger:** ____________________
- **End Condition:** ____________________
- **Duration:** _____ minutes (typical)
- **Resources Required:** ____________________
- **Input Materials:** ____________________
- **Output Products:** ____________________
- **Quality Checks:** ____________________

#### Process 2: [Process Name]
- **Start Trigger:** ____________________
- **End Condition:** ____________________
- **Duration:** _____ minutes (typical)
- **Resources Required:** ____________________
- **Input Materials:** ____________________
- **Output Products:** ____________________
- **Quality Checks:** ____________________

### Supporting Processes

#### Material Handling
- **Internal Transportation:** ____________________
- **Storage Operations:** ____________________
- **Inventory Management:** ____________________

#### Quality Assurance
- **Inspection Points:** ____________________
- **Testing Procedures:** ____________________
- **Rework Processes:** ____________________

#### Maintenance Activities
- **Preventive Maintenance:** ____________________
- **Breakdown Maintenance:** ____________________
- **Setup and Changeover:** ____________________

## 3.5 Product Scope

### Products to Model
| Product/SKU | Volume (%) | Complexity | Priority | Include in Model |
|-------------|------------|------------|----------|------------------|
| Product A | ___% | High/Medium/Low | 1 | [ ] Yes [ ] No |
| Product B | ___% | High/Medium/Low | 2 | [ ] Yes [ ] No |
| Product C | ___% | High/Medium/Low | 3 | [ ] Yes [ ] No |
| Product D | ___% | High/Medium/Low | 4 | [ ] Yes [ ] No |

### Product Characteristics
- **Product Mix Variability:** ____________________
- **Seasonal Patterns:** ____________________
- **Customisation Requirements:** ____________________
- **Quality Specifications:** ____________________

## 3.6 Time Scope

### Temporal Boundaries
- **Simulation Start Time:** ____________________
- **Simulation End Time:** ____________________
- **Warm-up Period:** _____ hours/days
- **Analysis Period:** _____ days/weeks/months

### Operating Patterns
- **Shift Schedule:** ____________________
- **Working Days per Week:** _____
- **Seasonal Variations:** ____________________
- **Holiday Shutdowns:** ____________________

### Historical Data Period
- **Data Start Date:** ____________________
- **Data End Date:** ____________________
- **Total Data Period:** _____ months
- **Data Completeness:** _____%

## 3.7 Assumptions & Constraints

### Key Assumptions
1. ____________________
2. ____________________
3. ____________________
4. ____________________
5. ____________________

### Model Constraints
- **Budget Limitations:** £____________________
- **Timeline Constraints:** ____________________
- **Resource Availability:** ____________________
- **Technology Limitations:** ____________________
- **Data Availability:** ____________________

### Simplification Decisions
| Real-World Complexity | Model Simplification | Justification |
|----------------------|---------------------|---------------|
| | | |
| | | |
| | | |

## 3.8 Interface Points

### Model Inputs
- **Demand Patterns:** External demand forecasts
- **Resource Availability:** Staffing and equipment schedules
- **Material Supply:** Raw material delivery schedules
- **External Dependencies:** Utility availability, support services

### Model Outputs
- **Performance Metrics:** KPIs and operational measures
- **Resource Utilisation:** Equipment and staff utilisation
- **Bottleneck Analysis:** Constraint identification
- **Improvement Recommendations:** Optimisation opportunities

### Data Exchange Requirements
- **Input Data Format:** CSV, JSON, database connection
- **Output Data Format:** Reports, dashboards, API feeds
- **Update Frequency:** Real-time, hourly, daily, weekly
- **Integration Requirements:** MES, ERP, quality systems

---

**Scope Validation Checklist:**
- [ ] All stakeholders agree on scope boundaries
- [ ] Included processes clearly defined
- [ ] Exclusions explicitly documented
- [ ] Resource requirements identified
- [ ] Timeline realistic for scope
- [ ] Success criteria align with scope

*Clear scope definition is critical for project success and stakeholder alignment throughout the simulation development process.*