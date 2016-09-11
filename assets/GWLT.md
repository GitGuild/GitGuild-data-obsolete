# GWLT Asset Definition

Wallet Guild Coins are claims against the Wallet Guild Treasury. The usual way GWLT is created is by earning XP. GWLT are earned 1:1 with XP.

GWLT may be issued for reasons other than earning, without XP. For istance, GWLT issued as a reimbursement for expenses do not deserve XP. These cases are voted on individually.

### Roles

 + Member
 + Service Provider

All Wallet Guild members are peers in the GWLT network. Any member may unilaterally transfer their GWLT to another by submitting a signed entry to the ledger. Members may redeem earned GWLT at a penalty of 1% per day from the day of the request, subject to fees and availability.

##### Member Withdrawal Table

To help explain the member withdrawals, this actuary table shows the expected yield assuming a hypothetical GWLT price of 1 chicken (CHKN).

| Days since request | Penalty | GWLT Redeemed | Yield |
|--------------------|---------|--------------|-------|
| 0 | 100% | 1 | 0 CHKN |
| 1 | 99% | 1 | 0.01 |
| 2 | 98% | 1 | 0.02 |
| 3 | 97% | 1 | 0.03 |
| n (< 100) | (100 - n)% | 1 | n / 100 |
| 100 | 0% | 1 | 1 |

Service Providers are outside of the Wallet Guild, and unable to receive payment in GWLT. As such, they are not subject to time penalties, and may receive Treasury withdrawals immediately.

### Funds

Funds may be established by contract, to hold assets on behalf of the Treasury. These may elect cosigners to manage assets only with 90% approval, as per the Change Treasury Sign Policy.

Funds may charge up to 1% for withdrawal processing.

### Revenue

This guild will offer support and possibly other services to wallet operators. Details to be arranged in later contracts.

### Sponsorships

For every 1 non-sponsorship GWLT issued, an additional 1% GWLT will be issued and allocated to the Git Guild Treasury. For instance, if 2.2 GWLT are issued to a member, 0.022 GWLT are to be issued to the Git Guild Treasury.

##### Sponsorship Table

| Name | Recipient | Asset | Percent on Issue |
|------|-----------|-------|------------------|
| Git Guild | FX:GWLT:GitGuild | GWLT | 1% |
| TAPP Guild | FX:GWLT:TAPPGuild | GWLT | 4% |
