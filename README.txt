Description
-----------

A drupal module that will deny userpoints being awarded for referrals via the referral module if the same user has been invited by a user and points awarded via the userpoint_invite module. The weights of the invite and referral modules are altered to ensure that any points given by the userpoint_invite module happen first, and then the points that are attempting to be offered by the my_referral_userpoints module are denied. Note that this denies poitns for both the referrer and the referee (assuming that invite rewarded both of them instead.).
