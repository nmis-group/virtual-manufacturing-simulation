# 7. Experimentation

## 7.1 Experiments to Perform

| Experiment ID | Experiment Type | Description | Priority | Resources Required |
|---------------|-----------------|-------------|----------|-------------------|
| **EXP001** | What-If Analysis | Evaluate impact of process changes | High | 2 weeks, simulation analyst |
| **EXP002** | Sensitivity Analysis | Test model response to parameter variations | High | 1 week, statistician |
| **EXP003** | Optimisation | Find optimal operating parameters | Medium | 3 weeks, optimisation specialist |
| **EXP004** | Monte Carlo | Assess uncertainty and risk | Medium | 1 week, risk analyst |
| **EXP005** | Scenario Planning | Compare strategic alternatives | High | 2 weeks, business analyst |

## 7.2 What-If Analysis Framework

### Experiment EXP001: What-If Analysis

#### Objective
Evaluate the impact of proposed process changes on manufacturing performance

#### Scenarios to Test
| Scenario ID | Scenario Name | Description | Key Changes |
|-------------|---------------|-------------|-------------|
| **S001** | Baseline | Current state operations | No changes |
| **S002** | Additional Machine | Add one production machine | +1 machine capacity |
| **S003** | Extended Hours | Increase operating hours | 16 hours/day → 20 hours/day |
| **S004** | Reduced Batch Size** | Smaller production batches | Batch size: 100 → 50 units |
| **S005** | Automation Upgrade | Implement automated material handling | -2 operators, +AGV system |

#### Parameters to Modify
| Parameter | Baseline Value | Scenario Variations | Expected Impact |
|-----------|----------------|-------------------|-----------------|
| **Production Capacity** | _____ units/hour | +25%, +50%, +100% | Increased throughput |
| **Operating Hours** | _____ hours/day | +2, +4, +8 hours | Extended production |
| **Batch Size** | _____ units | -25%, -50%, +25% | Inventory and flow changes |
| **Automation Level** | ____% | +20%, +40%, +60% | Labour and efficiency changes |

#### Output Metrics
- **Throughput:** Units produced per day/week
- **Resource Utilisation:** Equipment and labour utilisation
- **Cycle Time:** End-to-end production time
- **Work-in-Progress:** Average inventory levels
- **Cost per Unit:** Total cost divided by units produced

## 7.3 Sensitivity Analysis Framework

### Experiment EXP002: Sensitivity Analysis

#### Objective
Determine which parameters have the greatest impact on model performance

#### Parameters for Sensitivity Testing
| Parameter | Base Value | Test Range | Increment | Metric Monitored |
|-----------|------------|------------|-----------|------------------|
| **Demand Rate** | _____ units/day | ±40% | 10% | Throughput, utilisation |
| **Processing Time** | _____ minutes | ±30% | 5% | Cycle time, capacity |
| **Setup Time** | _____ minutes | ±50% | 10% | Efficiency, throughput |
| **Machine Reliability** | ____% | ±20% | 5% | Availability, output |
| **Quality Rate** | ____% | ±10% | 2% | Rework, throughput |

#### Analysis Methods
- **One-at-a-Time (OAT):** Vary each parameter individually
- **Design of Experiments:** Factorial design for interactions
- **Regression Analysis:** Quantify parameter relationships
- **Tornado Diagrams:** Visualise sensitivity rankings

#### Expected Outcomes
- Identification of most critical parameters
- Quantification of parameter impact
- Understanding of parameter interactions
- Prioritisation for future monitoring

## 7.4 Optimisation Studies

### Experiment EXP003: Process Optimisation

#### Optimisation Objectives
| Objective | Weight | Current Performance | Target Performance |
|-----------|--------|-------------------|-------------------|
| **Maximise Throughput** | 40% | _____ units/day | _____ units/day |
| **Minimise Cost** | 30% | £_____ per unit | £_____ per unit |
| **Minimise Cycle Time** | 20% | _____ hours | _____ hours |
| **Maximise Quality** | 10% | ____% first pass | ____% first pass |

#### Decision Variables
| Variable | Type | Range | Current Value | Constraints |
|----------|------|-------|---------------|-------------|
| **Number of Machines** | Integer | 1-10 | _____ | Budget, space |
| **Batch Size** | Continuous | 10-200 | _____ | Quality, storage |
| **Shift Pattern** | Categorical | 1/2/3 shifts | _____ | Labour availability |
| **Buffer Sizes** | Integer | 0-100 | _____ | Space constraints |

#### Optimisation Algorithm
- **Method:** Genetic Algorithm/Simulated Annealing/OptQuest
- **Population Size:** 50
- **Generations:** 100
- **Convergence Criteria:** <1% improvement over 10 generations

#### Constraints
- **Budget Constraint:** Total investment ≤ £_____
- **Space Constraint:** Floor area ≤ _____ m²
- **Time Constraint:** Implementation ≤ _____ months
- **Quality Constraint:** First pass yield ≥ _____%

## 7.5 Monte Carlo Analysis

### Experiment EXP004: Uncertainty Analysis

#### Objective
Assess impact of uncertainty and variability on model predictions

#### Uncertain Parameters
| Parameter | Distribution | Parameters | Source of Uncertainty |
|-----------|--------------|------------|----------------------|
| **Demand Variability** | Normal | μ=_____, σ=_____ | Market fluctuations |
| **Processing Time** | Triangular | min=_____, mode=_____, max=_____ | Operator variability |
| **Machine Failures** | Exponential | λ=_____ | Equipment reliability |
| **Quality Issues** | Binomial | n=_____, p=_____ | Process variation |

#### Risk Analysis
- **Downside Risk:** Probability of not meeting targets
- **Upside Potential:** Probability of exceeding expectations
- **Value at Risk:** 95th percentile performance
- **Expected Value:** Mean performance across scenarios

#### Output Analysis
- **Confidence Intervals:** 90%, 95%, 99% confidence levels
- **Risk Metrics:** Probability distributions for key outcomes
- **Scenario Probabilities:** Likelihood of different outcomes
- **Sensitivity to Uncertainty:** Most impactful uncertain factors

## 7.6 Scenario Planning

### Experiment EXP005: Strategic Scenario Analysis

#### Business Scenarios
| Scenario | Description | Probability | Time Horizon | Key Assumptions |
|----------|-------------|-------------|--------------|-----------------|
| **Growth Scenario** | 50% demand increase | 30% | 2 years | Market expansion |
| **Efficiency Focus** | Cost reduction emphasis | 40% | 1 year | Lean implementation |
| **Technology Disruption** | Automation investment | 20% | 3 years | Capital availability |
| **Market Decline** | 25% demand reduction | 10% | 1 year | Economic downturn |

#### Scenario Parameters
| Parameter | Growth | Efficiency | Technology | Decline |
|-----------|--------|------------|------------|---------|
| **Demand Level** | +50% | Baseline | +20% | -25% |
| **Labour Cost** | +10% | -15% | -30% | Baseline |
| **Equipment Investment** | £50k | £0 | £200k | £0 |
| **Quality Target** | 98% | 99% | 99.5% | 95% |

## 7.7 Experimental Design

### Design of Experiments (DOE)

#### Factorial Design
**Factors:** 3-5 key parameters
**Levels:** 2-3 levels per factor
**Replicates:** 5-10 runs per combination
**Total Runs:** _____ simulation runs

#### Factors and Levels
| Factor | Low Level | Medium Level | High Level |
|--------|-----------|--------------|------------|
| **Factor A: Demand Rate** | -20% | Baseline | +20% |
| **Factor B: Machine Speed** | -10% | Baseline | +10% |
| **Factor C: Batch Size** | -50% | Baseline | +50% |

#### Response Variables
- **Primary Response:** Throughput (units/day)
- **Secondary Responses:** Cost, cycle time, utilisation
- **Interaction Effects:** Factor combinations

### Statistical Analysis Plan
- **ANOVA:** Identify significant factors
- **Regression:** Develop predictive models
- **Interaction Analysis:** Factor interactions
- **Model Validation:** Check regression assumptions

## 7.8 Experiment Execution

### Experiment Protocol
1. **Setup:** Configure simulation parameters
2. **Warm-up:** Run model to steady state
3. **Data Collection:** Record specified metrics
4. **Replication:** Repeat for statistical validity
5. **Analysis:** Statistical analysis of results

### Data Collection
| Run ID | Scenario | Replication | Start Time | End Time | Status |
|--------|----------|-------------|----------