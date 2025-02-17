### Allow users to check the status of transaction (pending, success,failed).
Check transaction status [transaction_id]

### Allow users to cancel transaction if it is still pending.
CancelTransaction [transaction_id]

### set daily transaction limit.
SetTransactionLimit [user_id] [limit_type] [amount]

### Allow users to Block/Unblock other users 
BlockAccount [user_id]
UnblockAccount [user_id]

### Allow users to refer friends and earn rewards
ReferUser [referrer_id] [referee_phone_number]
