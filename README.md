# General Variables
```
{user.name}
{user.mention}
{user.id}
{user.avatar_url}
{guild.member_count}
{guild.name}
{guild.icon_url}
```
            
# Command Specific Variables

## Infraction Module:
  All General Variables + 
  ```
  {infraction.moderator.name}
  {infraction.moderator.mention}
  {infraction.moderator.id}
  {infraction.moderator.avatar_url}
  {infraction.reason}
  {infraction.timestamp}
  {infraction.id}
  ```
  
## Order Module:
  All General Variables + 
  ```
  {order.customer}
  {order.designer}
  {order.staff} - whoever logged the order, dont bother using if the designers log their orders
  {order.product}
  {order.price}
  {order.timestamp}
  {order.id}
  ```
  
