<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree, oneFour, oneFive;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo, fourThree;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">JEWBALL SUPER FANTASY FOOTBALL CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(one)}>Section 1: Roster</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneOne)}>1.1 Positional Breakdown</h4>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneOneOne)}>1.1.1 Position Maximums</h5>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneTwo)}>1.2 Trading</h4>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneTwoOne)}>1.2.1 Trade Collusion</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneTwoTwo)}>1.2.2 Lending Players Prohibition</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneTwoThree)}>1.2.3 Trade Deadline</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneTwoFour)}>1.2.4 Trade Restrictions</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneTwoFive)}>1.2.5 Veto/Trade Process</h5>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneThree)}>1.3 Waiver Wire</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneFour)}>1.4 Taxi Squad</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneFive)}>1.5 Taxi Squad Poaching</h4>
    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(two)}>Section 2: Drafting</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoOne)}>2.1 Start-Up Draft</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoTwo)}>2.2 Draft Order</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoThree)}>2.3 Rookie Drafts</h4>
    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(three)}>Section 3: Scoring System</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(threeOne)}>3.1 Scoring System</h4>
    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(four)}>Section 4: Season Schedule</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fourOne)}>4.1 Regular Season</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fourTwo)}>4.2 Playoffs</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fourThree)}>4.3 Seeding Tiebreakers</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(five)}>Section 5: Tanking Policy</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fiveOne)}>5.1 League Tanking Policy</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(six)}>Section 6: Orphan Teams and Manager Replacement</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixOne)}>6.1 Removing Managers</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixTwo)}>6.2 Retiring Managers</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixThree)}>6.3 Replacing Orphaned Teams</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(seven)}>Section 7: League Finances</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenOne)}>7.1 League Dues</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixTwo)}>7.2 Payout</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixThree)}>7.3 Raising Dues</h4>
    
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 Roster Breakdown</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Positional Breakdown</h3>
    
    <p>32 Total Players</p>
    
    <p class="underscore">Starters</p>
    <ul>
        <li>QB</li>
        <li>RB</li>
        <li>RB</li>
        <li>WR</li>
        <li>WR</li>
        <li>WR</li>
        <li>TE</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>FLEX (QB/RB/WR/TE)</li>
    </ul>
    
    <p>15 Bench</p>

    <p>2 IR Spots (Player must be labeled as IR or PUP by actual NFL team)</p>

    <p>5 Taxi Squad Spots<p>
    
        <h4 bind:this={oneOneOne}>1.1.1 Position Maximums</h4>
        
        <div class="subBlock">
            <table class="positionMaximums">
                <tbody>
                <tr><td>QB</td><td class="right">6</td></tr>
                <tr><td>RB</td><td class="right">18</td></tr>
                <tr><td>WR</td><td class="right">18</td></tr>
                <tr><td>TE</td><td class="right">10</td></tr>
                </tbody>
            </table>
        </div>


    <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Trading</h3>
    
    <p>Trading of players and draft picks (up to 3 drafts away) is allowed. Trades will process immediately and will be reversed if vetoed or suspected of collusion. Final decision on trade vetoes and collusion will be made by the commissioner council. Tradable assets include players, draft picks, and FAAB $.</p>
    
    <h4 bind:this={oneTwoOne}>1.2.1 Trade Collusion</h4>
    <div class="subBlock">
        <p>If any owners are suspected of accepting bribes/offering bribes to enhance their/another owners team via trade, trading any assets other than fantasy players, draft picks, FAAB $, or otherwise found guilty of engaging in any form of collusion*, all parties involved in the trade will be susceptible to punishment. The punishments will go as followed:</p>
        
        <ul>
            <li>First Offense – Immediate freeze on all future transaction types for the next 5 weeks and a loss of ALL current FAAB budget</li>
            <li>Second Offense – Immediate freeze on all transaction types for the next 18 weeks of regular season and playoff fantasy football games, plus a loss of the nearest future 1st round pick and the nearest future 2nd round pick</li>
            <li>Third Offense – A league meeting of all members not involved in any of the improper trades/activity in question will take place to discuss next steps</li>
        </ul>

        <p>All trades that are found guilty of collusion will be reversed/denied. If the trade had affected the outcome of previous games, the results of those games will be revised.  </p>

        <p>The commissioner will err on the side of letting owners manage their teams the way they see fit. Any collusion will need to be clear. The commissioner reserves the right to step in and at the very least assess the thinking of any team involved in a heavily lop-sided trade. </p>
    </div>

    <h4 bind:this={oneTwoTwo}>1.2.2 Lending Players Prohibition</h4>
    <div class="subBlock">
        <p>Any player traded from a team may not be re-acquired via trade within the same season of the original trade (up until week 13, does not include post-championship). Any teams involved in this behavior will be subject to the aforementioned collusion punishments.</p>
    </div>
    
    <h4 bind:this={oneTwoThree}>1.2.3 Trade Deadline</h4>
    <div class="subBlock">
        <p>The trade deadline will be set for the Monday after the week 13 games of the NFL season.</p>
    </div>
    
    <h4 bind:this={oneTwoFour}>1.2.4 Trade Restrictions</h4>
    <div class="subBlock">
        <p>You will not be able to trade draft picks that are more than 3 drafts away. For example, during the 2021 season you cannot trade any picks in or after the 2025 draft. You may only trade FAAB $ from the current season.</p>
    </div>
    
    <h4 bind:this={oneTwoFive}>1.2.5 Veto/Trade Process</h4>
    <div class="subBlock">
        <p>A veto may only be carried out if a majority consensus is reached among the commissioner council on the invalidity of the trade (though players may suggest for a trade to be looked in to). A veto may only be carried out on the basis of collusion or, based on the discretion of the council, extreme and league breaking inequality which threatens to skew the balance of power among leaguemates with little return for the opposite side of the trade.</p>
    </div>
    
    
    
    <h3 class="subSectionHeading" bind:this={oneThree}>1.3 Waiver Wire</h3>

    <p>FAAB Waiver wire system. Each team will begin the season with $200. Although you may trade FAAB budget, note that your total balance CANNOT exceed $200. Also note that budget does not rollover from year to year, and resets after the rookie draft. $0 bids are allowed. Bids will process Tuesdays and Saturdays at 8AM EST. After waivers clear on Saturdays all waiver wire players will be released and become free agents.</p>

    <p>FAAB budgets will reset each season in following the rookie draft.</p>



    <h3 class="subSectionHeading" bind:this={oneFour}>1.4 Taxi Squad</h3>

    <p>Each team will have 5 taxi squad spots. Players on the taxi squad do not count against the active roster limit and cannot be started unless promoted to the main roster. To be eligible for taxi squad, a player must have no more than 2 years of experience in the NFL. Experience is calculated based on completed NFL seasons.</p>

    <p>The deadline to move players into the taxi squad is the start of the regular season. After this point, no additional players may be added. However, players may be promoted from the taxi squad to active roster at any time during the season. Once a player is removed from the taxi squad, they are no longer eligible to return to it.</p>

    <h3 class="subSectionHeading" bind:this={oneFive}>1.5 Taxi Squad Poaching</h3>

    <p>Any player on any manager's Taxi Squad is subject to being poached by opposing managers. A player may be poached anytime during the season or offseason (except during playoffs). Managers must make their claim on a Taxi Squad player they wish to poach from another manager between Tuesday and Friday. Once a player is claimed, the manager who has said player on their Taxi Squad has 48 hours to respond. In response, they have the choice to either elevate the claimed player from
their Taxi Squad onto their roster's bench, or to accept the claim from the opposing manager. If the claim is accepted, then the manager who made the claim must send a compensatory draft pick equal to or greater than the round the claimed player was slected in +1 (If a player on Taxi Squad was drafted in start-up, then compensatory pick will be based player ADP in past rookie drafts).</p>

    <p>For example, if a player was drafted in the 5th round, then compensatory pick would be a 4th or better. If a player on Taxi Squad was drafted 3rd round, then compensatory pick would be a 2nd or higher. It is slightly different for first round selections, however. A late 1st round pick on Taxi Squad (picks 6-12) will require a 1st and 2nd in compensation. An early 1st round pick (picks 1-6) will require two 1sts in compensation.</p>

    <p>Managers have 5 attempts at poaching players between rookie drafts. The commissioner will keep track of the number of poaching attempts each manager has. An attempt counts as any offer sent for a Taxi Squad player.</p>

    <h2 class="sectionHeading" bind:this={two}>Section 2 Drafting</h2>

    <h3 bind:this={twoOne}>2.1 Start-Up Draft</h3>
    <p>The start-up draft will take place once the league has filled and every manager has paid their league fee. The startup draft order will be randomized in a reasonable fashion and published on sleeper. The draft wll be a 30-round snake-draft, 3rd-round reversal, with the first 5 rounds having a 10-minute timer. Players are expected to be active and present at the draft party (or at least be active on the app to make your picks in a timely manner). Following the first 5 rounds, the pick timer will be expanded to 8 hours per pick, with the timer being paused overnight. Those who fail to pick in the alloted time during the draft will be auto-picked.</p>
    <p>Start-up draft picks are tradeable before and during the draft. If a trade is being discussed, inform the commissioner and the timer will be paused for negotiations (only during first 5 rounds). Timer will be resumed following the trade, however, the timer will not restart and will resume from where it was last at (so let the commissioner know to pause the timer as soon as possible).</p>

    <h3 bind:this={twoTwo}>2.2 Draft Order</h3>
    <p>The draft order each year for rookie drafts will be determined by non-playoff teams' Max Point For (Max PF) from the previous season (in reverse order), then by the playoff teams' final standings.</p>
    <p>    <p/>
    <p>Draft Order:</p>
    <p>    1) Max PF</p>
    <p>    2) Max PF</p>
    <p>    3) Max PF</p>
    <p>    4) Max PF</p>
    <p>    5) Max PF</p>
    <p>    6) Max PF</p>
    <p>    7) Winner of the 5th Place Game</p>
    <p>    8) Loser of the 5th Place Game</p>
    <p>    9) Loser of the 3rd Place Game</p>
    <p>    10) Winner of the 3rd Place Game</p>
    <p>    11) Runner-Up</p>
    <p>    12) Champion</p>
    <p>    <p/>
    <p>The draft will be in a linear fashion, meaning a team with pick 1.01 will also have pick 2.01, 3.01, etc.<p/>
    
    <h3 bind:this={twoThree}>2.3 Rookie Drafts</h3>
    <p>Each offseason, there will be a 4-round rookie draft held no earlier than one week after the real NFL draft and no later than one month after it. The rookie draft will not commence until all managers contribute their yearly buy-in. Each team will have 24 hours to make their pick, with managers being expected to make their picks in a timely manner. Draft picks may be traded anytime. No timer pauses available.</p>
    
    <h2 class="sectionHeading" bind:this={three}>Section 3 Scoring System</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>*The scoring system will never change without a majority league vote.*</p>

    <p class="underscore">Passing</p>
    <ul>
        <li>Passing Yards: 1 point every 25 yards (0.04 per yard)</li>
        <li>Passing TD: 4</li>
        <li>2-Pt Conversion: 2</li>
        <li>Pass Intercepted: -2</li>
        <li>QB Sack: -1</li>
    </ul>

    <p class="underscore">Rushing</p>
    <ul>
        <li>Rushing Yards: 1 point every 10 yards (0.10 per yard)</li>
        <li>Rushing TD: 6</li>
        <li>2-Pt Conversion: 2</li>
    </ul>

        <p class="underscore">Receiving</p>
    <ul>
        <li>Reception: 0.5</li>
        <li>Receiving Yards: 1 point every 10 yards (0.10 per yard)</li>
        <li>Receiving TD: 6</li>
        <li>2-Pt Conversion: 2</li>
        <li>Tight End Premium: 1 per reception</li>
    </ul>

        <p class="underscore">Miscellaneous</p>
    <ul>
        <li>Fumble Lost: -2</li>
        <li>Fumble Recovery TD: 6</li>
    </ul>

    <h2 class="sectionHeading" bind:this={four}>Section 4 Season Schedule</h2>
   
    <h3 bind:this={fourOne}>4.1 Regular Season</h3>
    <p>The regular season runs from Week 1 through Week 14 of the NFL schedule. Each week two teams face off in a head-to-head game as outlined by the schedule. Ties are recorded as ties.</p>

    <h3 bind:this={fourTwo}>4.2 Playoffs</h3>
    <p>At the end of Week 14, 6 qualifying teams will make the playoffs. The first round of playoffs will commence in week 15. The top-2 seeds will receive a first-round bye. Playoff seeding is determined as described below.</p>

    <p>At the end of week 14, the 6 teams who failed to make playoffs will be placed into a consolation bracket. The team which wins the consolation bracket will be awarded an extra pick at the end of Round 2 of the upcoming rookie draft (Pick 2.13). This pick cannot be traded.</p>

    <h3 bind:this={fourThree}>4.3 Seeding Tiebreakers</h3>
    <p>Playoff seeding will be structured as follows, with priority starting from top to bottom:</p>

    <ol>
        <li>Overall Record</li>
        <li>Points For (PF)</li>
        <li>Head 2 Head Record</li>
        <li>Higher Points Against (PA)</li>
    </ol>

    <h2 class="sectionHeading" bind:this={five}>Section 5 Tanking Policy</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>No team may intentionally fail to submit their best available starting lineup, whether intentionally or through indifference. Managers are expected to use their best efforts to set their best available lineup every week of competition, even if they are well out of playoff contention. It is understood that managers may play hunches on who to start and won't always start the player who scores the most points, however, if a manager is obviously benching star players and clear starters in favor of marginal or injured players will be subject to commissioner sanctions on first offense. Remember, draft order is determined by Reverse Max PF, so there is no reason to not try to win.</p>

    <p>In a similar vein, a manager may not (without good reason) cut players who are obviously valuable to their team, and who may contribute to the starting lineup. If a manager is found guilty of "dumping" their team, they will have manager sanction placed on them, and will be forced to re-acquire the players they had dumped.</p>

    <p>Finally, a manager who fails to submit a starting lineup or fails to replace inactive players who are injured, benched, or suspended is subject to commissioner sanctions. A manager showing indifference is different from an unavailable manager, if you will be unable to care for your team for an extended period of time, inform the commissioner so they can at least manage the start/sits in your lineup. Repeated indifference to at least set your starting lineup will result in removal from the league.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Orphan Teams and Manager Replacement</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>Commissioner reserves the right to remove any manager (with no refund available) whom fails to consider and abide by the following:</p>
   <ul>
        <li>League payments should be made by the deadline</li>
        <li>No form of cheating, collusion, bribery, nor throwing will be tolerated at any time</li>
        <li>Be consistently active, returning texts and trade offers in a timely manner</li>
        <li>Avoid conduct or transactions which may be detrimental to the sanctity of the league</li>
        <li>Abide by ALL league rules listed here (and rules not listed here which may be considered general courtesy), abide by ALL commissioner rulings once they have been made</li>
    </ul>
    
    <h3 bind:this={sixTwo}>6.2 Retiring Managers</h3>
    <p>In the case a manager chooses to retire from the league, it is requested that they do so during the offseason at least 2 months before the season begins. In the case that one chooses to retire in the appropriate timeframe AND is able to find a replacement manager to takeover their team, they will get a full refund (including deposits on future years). In the case the retiring manager fails to find a replacement, they will only be guarenteed a refund of their deposit for the current year. Finally, any other retirement situation will result in NO REFUND WHATSOEVER. This includes midseason dropouts, abondonment, etc.</p>
    
    <h3 bind:this={sixThree}>6.3 Replacing Orphaned Teams</h3>
    <p>In the case that a manager drops from the league midseason, the commissioner will ONLY set weekly lineups for the orphaned team, avoiding any direct control. A replacement manager should be found as quickly as possible. To aid in this, incoming manager should be offered at least a 50% discount on their entrance fees.</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at {dues}$. Dues will be collected through Venmo (my account name is @SCXMMER), as it will allow for public transactions which can easily be tracked by the whole league. If you prefer an alternative payment method, please contact commissioner. Collection will be sent out no later than 07/07. All managers must be fully paid up before the start of regular season. In the event that a manager fails to pay before the deadline, a 10% penalty will be added to their payment and will go towards the payouts at the end of the year.</p>

    <p>IMPORTANT: It is also required that managers pay ahead of time for future year buy-ins IF they wish to trade future draft picks (e.g., if I wish to trade away my 2026 1st, I am required to pay my 2026 buy-in fee). You must pay 100% of the future buy-in upfront BEFORE completing any trades involving that year's draft picks.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: {dues * 9}$</li>
        <li>2nd place: {dues * 2}$</li>
        <li>3rd place: {dues}$</li>
    </ul>
    <p>In the event that a manager was fined due to late payment, their extra fee will be added to the winner's payout.</p>
    
    <h3 bind:this={sevenThree}>7.3 Raising Dues</h3>
    <p>A ⅔ majority vote is required in order to raise league dues. In the event that a manager is no longer financially comfortable with the buyin, finding a co-manager to split the cost is reccomended.</p>

</div>
