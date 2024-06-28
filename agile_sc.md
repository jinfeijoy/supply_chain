# week 1: supply chain planning
## demand planning
* data aggregation: 
    * by default, the forcast is done at SKU level and then aggregate to category level, product line and business unit level for sr exective 
    * unless you are dealing with product that are life saving, require freshness, or have other market and business constrains, you should be able to forecast at the monthly level
* identify influencing factor
    * 
## supply planning
* supply planning is the process of confirming the available internal and external capacity for the periods of interest and affirming whether the projected demand (from demand planning) can be met for those periods.
* the supply planner must work with external suppliers to affirm capacity availability. The planner will go through similar steps as they went through with the internal manufacturing facilities.
* The other crucial activity in the supply planning process is to ensure raw materials and semi-finished components are available to make the required quantity by the timeframe specified in the approved demand plan. Internally, the supply planner may work directly with the material suppliers or go through a materials coordinator to confirm material availability. Supply planning needs to work with external manufacturers' contacts to confirm material availability.
## constrained forecast 
* As the name indicates, the constrained forecast is a more realistic demand goal that the company as a whole can achieve. The idea is that demand can only be met when resources and capacity are available. 
## measurement 
* MAD: mean absolute deviation
* MSE: mean square error
* MAPE: mean absolute percentage error
# week2: inventory management 
## steady state demand: no demand variability
* Steady-state demand, as the name implies, is a situation without variability. Demand is constant and predictable (with/without lead time)
    * lead time: 
        * Manufacturing lead time
        * Freight lead time (ocean or air)
        * Custom and processing lead time at the ports
        * Last-mile delivery lead time
* reorder time need to consider lead time
## inventory management with demand variability
* source of variability
    * Transportation disruption due to weather or political events
    * Shortage of materials or components due to labor disputes
    * Unexpected increase in demand due to factors not previously considered
    * (Depending on the season (e.g., summer, winter, holidays) or political calendar (e.g., elections), supply chain professionals may elect to increase lead time or inventory build-up to counter potential transportation disruptions. They may also elect to buy in advance if they expect a labor or material shortage.)
* ways to counter variability
    * Increase available information: The more information we have, the better we can assess the impact at a broader level. Suppose we have information about consumer sentiment regarding pandemics. We may be able to shorten the required lead time to respond to the abrupt increase in demand for certain consumable goods. This information can influence our demand planning analysis.
    * Shorten lead times: The shorter the lead time to get raw materials into final products and onto retail shelves, the quicker the supply chain can respond to market changes. For example, if a supply chain lead time can be reduced from 30 to 5 days, there can be a quicker recovery from stockouts. Stockouts can also be avoided altogether if a surge in demand is detected early and a replenishment order is placed soon after.
    * Hold optimal safety stock: Holding optimal safety stock is like buying insurance for any unexpected events. The purpose of safety stock is to provide a cushion against unforeseen circumstances. The amount of safety stock to hold varies and needs to be reviewed and adjusted periodically due to changes in demand, variability in the system, and other factors.
* reorder point and safety stock

## inventory as a strategical tool to meet customer service level
## newsvendor model (one-period decision model)
* The standard newsvendor model is concerned with the amount of inventory to carry that would minimize understocking and overstocking costs.
* Overage costs are relatively simple to determine and consist of some standard components:
    * Salvage value: This is the amount of money one can reclaim at the end of the selling season. For example, retailers often mark down the price of day-old bread. Salvage value is the difference between the marked-down price and the retailer's price.
    * Inventory holding cost: This cost is associated with warehousing the inventory and is the cost of warehouse space (e.g., the lease) and the overhead to operate the area. It is usually estimated based on price per pallet or square foot.
    * Opportunity cost of capital: This is the amount of money that can be invested instead. For example, $10k in cash can be used to purchase inventory or can be put into an interest bearing account at a bank. The interest earned in this case can be the opportunity cost of using this money to purchase inventory. 
* estimating the underage cost can be trickier.
    * Goodwill cost: This is the cost of turning a customer away. This damages the company's reputation as the customer might get upset or frustrated and may think twice before placing another order in the future.
    * Expedite fees: This is the fee paid to have products available sooner. These fees can be paid to the logistic company for faster shipping or to the manufacturer to adjust their production schedule.
    * Increased supplier cost: Companies typically have at least two suppliers for the same item. The primary supplier will be the cheapest, and the second supplier may have a higher cost and only be used as a backup. The cost difference between the two can be considered an underage cost.
* The newsvendor model is often used to determine inventory levels for single-period, perishable items. (Seasonal items， Airline/concert tickets and hotel rooms）




