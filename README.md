A typical airline's organizational structure consists of divisions for marketing, operations, maintenance, and finance. The airline's daily operations are managed by the operations division, which also has control over ground crews, flight dispatchers, pilots, and flight attendants. 
Under such an organizational system,pilot staffing and training is one of the most complex and costly problems facing major airlines. If an airline does not manage the problem effectively, it wouldn't have made a significant profit in the competitive air transportation market. 
To solve the pilot staffing problem,  Our model will determine optimal pilot allocation. we design a simplified optimization model to minimize cost in assigning block hours to different pilots while satisfying the basic professional ethics.

<img width="346" alt="image" src="https://github.com/Tianzi0521/JHU-Pilot-staffing-plan/assets/142115795/e74f229c-1961-4c5f-88fe-f1f818e8be89">


Decision variables:
xit: Binary variable indicating whether pilot i is assigned to flight duty at time t (1 if assigned, 0 otherwise)
yi: Binary variable indicating whether pilot i incurs fixed costs (1 if yes, 0 otherwise)
bi: block hours assigned to pilot i
shortaget: the amount of hours cannot be satisfied at each time period

Input values:
Cit: represents the cost of assigning pilot i to a duty or flight at time t.
Fi:  the fixed cost associated with the pilot i's pay protection or other fixed obligations.
St: the penalty cost per unit of shortage in block hours at time t.


We got our data from the Golden Epaulettes Aviation - A globally recognized, top-ranking institute for ground training in aviation. The official data from it discloses that a commercial airline pilot flies between 40-60 hours per week and the fixed cost around 30-80 per pilot. We gather essential input values for our model by considering not only fixed and penalty costs, flight block hour requirements, operational limits, and pilot qualifications but also the standard cost of a flight, availability, and maximum flying hours. The model optimizes pilot allocation and produces allocations that optimize costs while preserving coverage, methodically allocate resources to meet demand, and comply with safety standards because it properly reflects the limits and objectives of the real world. Within the limitations, this method ensures effective coverage and efficient operations by optimizing pilot use. 

