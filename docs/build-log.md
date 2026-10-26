# Uber V - Electric Bicycle Conversion

## Project Overview

**Objective:** Design a custom electric bicycle conversion using a vintage Cannondale Super V platform. The project will focus on battery characterization, electrical powertrain design, mechanical integration, and cost optimization.

I intend to document the engineering process, including design decisions, measurements, failures, costs, and revisions. A major goal is to fund the project through part-time delivery work rather than using personal savings.



## Build Log

### 2026-10-25

**What I did:** I gave the bike a clean with warm soap and water and dried it off. Here are the [before and after cleaning photos](images/2026-10-25-bike-cleaning/). I also did some more research on how I should go about battery testing.

**What I learned:** I learned that something that I will need is a way to measure the internal resistance of each cell. Normal battery testers like the ones I have been researching do not have the most accurate testing methods for internal resistance. A dedicated 1kHz AC milliohm meter is what I will need to get accurate readings. These are not the cheapest of items but I think this [listing](https://www.amazon.com/dp/B0F8P45N35?_encoding=UTF8&psc=1) is the way to go despite its cost of $64.99. It should make the voltage and internal resistance measurements go by much faster and turn out more accurate than other methods. 

**What is unknown** The shipping on the cells still says "Label Created" so I do not know what to think. I am hoping for a couple days but it is just unknown.

**Future Plans** I still need to order the 1kHz tester and the battery tester to test the capacity of the cells. I want to make sure I make the right choice on this but I want to have the testers by the time the cells arrive. So I plan on ordering both tomorrow and updating the budget.md.


### 2026-10-24: Funding The Project

**What I did:** I made some major progress in gaining funding for this project. To give some background info a couple weeks ago I started delivering food on my bike with doordash. I then saw that uber eats was having a promotion for new drivers for $150 for your first 15 deliveries and that is valid for up to 3 times so $450 total. I had done 27 deliveries prior to today and the promotion was ending tomorrow, so I decided to knock the rest of it out today. As of October 24, my Uber Eats earnings for the week totaled $729.74, including $450 in promotional bonuses. My Uber wallet balance reached $822.94, including earnings from previous weeks. These figures are gross earnings before taxes and expenses.

**Current Project Budget:** So far, I have spent $288.26 on 500 reclaimed 18650 cells and related supplies. My goal is to finance the rest of the components only using money from deliveries and not withdrawing any money from my savings. Future costs will include battery testing equipment, a motor and controller, a BMS, mechanical components, and safety equipment.

**What is unknown** It is still unknown when the cells will arrive. FedEx tracking says the label has been created so I will estimate another 2-4 days.

**Future Plans:** I plan on taking a break from doing deliveries for a couple of weeks to split my time between this project and studying for my midterms. I am going to make time tomorrow to fully clean the bike and start planning my first LinkedIn post showcasing the plan for this project. I also need to order a battery tester so I have that in time for when the cells arrive.

### 2026-10-23: Virginia Ebike Law and Cell Testing Bottleneck

**What I did:** I did some research on Virginia Ebike law.

**What I learned:** It turns out that anything above 750 watt is no longer classified as an Ebike. Also with just throttle they are limited to 20mph and 28mph with pedal assist. [Source](https://law.lis.virginia.gov/vacode/title46.2/chapter1/section46.2-100/)

**What is unknown:** What I don't know is how hard it would be to just have the bike classified as a moped because that could fix the 750 watt limit. Also still unknown is when my 18650 cells will arrive. The order still says they are getting the order ready so I guess I would estimate another 3-7 days until I see them at my door.

**What to do next?:** I think going forward I am keeping my plan pretty much the same but I think I am going to have to figure out a way to program the controller to cap at 750 watts. I still want the ability to test the bike's full power but I don't want to risk having it be non-street legal and getting into a wreck or something. For the short term I want to give the bike a nice soapy clean because it is covered in dirt and after that I want to take measurements and document them and put pictures in the github along with the data.

**Unresolved:** It is unclear whether limiting the motor to 750W through software would follow Virginia's electric bicycle classification requirements. I need to verify this before treating the completed vehicle as road-legal.

**Additional problem:** Another problem I learned I will encounter with some research is the cell testing phase. I estimate that a complete capacity testing cycle could take around 8–15 hours per batch, depending on the initial charge level, testing current, and equipment. I will benchmark the actual duration using one tester before deciding whether additional units are worth purchasing. Each one costs around 40 dollars. So with a single 8 channel tester it would take somewhere from 500-950 hours of testing(**Estimate**).

### 2026-10-21: Ordered Cells Yesterday

**What I did:**  ordered 50 modem battery packs each with 10 18650 cells rated at 3200 mAh from battery hookup (total of 500 cells)

**What I expect:** I expect a mixed quality from the cells. I estimate 5 percent will be dead and 20 percent degraded. As for capacity I expect on the lowest end around 1600mAh but most on average around 2600mAh I hope.

**What is unknown:** I have no idea which mixture of cell brands I will get. Also unsure of how the internal resistances will differ. Additionally I have no way of knowing how many have survived after sitting for years uncharged.

**What to do next?:** Take measurements of the bike dimensions, set up battery tracking CSV, Check if my multimeter is sufficient, buy a battery tester to test capacity of cells. And hope cells don't take a month to arrive.




