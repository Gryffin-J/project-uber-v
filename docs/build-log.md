# Build Log

## 2026-10-23: Virginia Ebike Law and Cell Testing Bottleneck

**What I did:** I did some research on Virginia Ebike law.

**What I learned:** It turns out that anything above 750 watt is no longer classified as an Ebike. Also with just throttle they are limited to 20mph and 28mph with pedal assist. [Source](https://law.lis.virginia.gov/vacode/title46.2/chapter1/section46.2-100/)

**What is unknown:** What I don't know is how hard it would be to just have the bike classified as a moped because that could fix the 750 watt limit. Also still unknown is when my 18650 cells will arrive. The order still says they are getting the order ready so I guess I would estimate another 3-7 days until I see them at my door.

**What to do next?:** I think going forward I am keeping my plan pretty much the same but I think I am going to have to figure out a way to program the controller to cap at 750 watts. I still want the ability to test the bike's full power but I don't want to risk having it be non-street legal and getting into a wreck or something. For the short term I want to give the bike a nice soapy clean because it is covered in dirt and after that I want to take measurements and document them and put pictures in the github along with the data.

**Additional Problem:** Another problem I learned I will encounter with some research is the cell testing phase. With an 8 cell battery tester each charge and discharge phase could take somewhere from 6-12 hours(**Estimate**). Each one costs around 40 dollars. So with a single tester it would take somewhere from 750-1000 hours of testing(**Esitmate**). Luckily it is mainly passive but that is a huge chunk of time. My only real thought for how I could get past this is throwing more money into the testers so maybe 4 testers. But that would run me up to 160 dollars just for battery testers which will run up the total budget for the entire build. I think I will start with one tester and do a benchmark of how fast I can test cells and go from there.

## 2026-10-21: Ordered Cells Yesterday

**What I did:**  ordered 50 modem battery packs each with 10 18650 cells rated at 3200 mAh from battery hookup (total of 500 cells)

**What I expect:** I expect a mixed quality from the cells. I estimate 5 percent will be dead and 20 percent will be close to dead, maybe possibly revivable. As for capacity I expect on the lowest end like 1600mAh but most probably around 2600mAh I hope.

**What is unknown:** I have no idea which mixture of cell brands I will get. Also unsure of how the internal resistances will differ. Additionally I have no way of knowing how many have survived after sitting for years uncharged.

**What to do next?:** Take measurements of the bike dimensions, set up battery tracking CSV, Check if my multimeter is sufficient, buy a battery tester to test capacity of cells. And hope cells don't take a month to arrive.


