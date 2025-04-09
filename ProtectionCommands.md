# Protection System Command Reference
*v1.0 | Created: 2025-04-09*

## 🛡️ Protection Shorthand Commands

When using Command-K in the code editor, type:

| Shorthand | Expands To            | Protection Level |
|-----------|------------------------|------------------|
| `!cp`     | PROTECTED comment      | Highest          |
| `!cg`     | GUARDED comment        | High             |
| `!ci`     | INFO comment           | Medium           |
| `!cd`     | DEBUG comment          | Medium           |
| `!ct`     | TEST comment           | Medium           |
| `!cc`     | CRITICAL comment       | Highest          |

## 📝 Example Usage

### JavaScript Example
```javascript
// PROTECTED - DO NOT MODIFY
function processPayment(paymentDetails) {
  // Payment processing logic
}
```


Python Example
python# GUARDED - ASK BEFORE MODIFYING
def validate_user_credentials(username, password):
    # Authentication logic
HTML Example
html<!-- INFO - CONTEXT NOTE -->
<div class="payment-form">
  <!-- Payment form elements -->
</div>
CSS Example
css/* CRITICAL - BUSINESS LOGIC */
.security-element {
  display: none;
  visibility: hidden;
}
🔍 Scanner Command
To scan your project for code that should be protected:
/protect-scan
This will analyze your codebase and suggest appropriate protection levels.
🔄 Protection Status Command
To check the status of protected code in your project:
/protect-status
This will show all protected regions and their status.
💬 Protection Commands
CommandPurpose/protect-scanScan project for code that should be protected/protect-statusView all protected regions/protect-addAdd protection to selected code/protect-removeRemove protection (requires confirmation)/protect-approveApprove modification of GUARDED code
🔄 Protection Mode Behaviors
In RESEARCH Mode (Ω₁)

Protected code is identified and documented
No modifications are attempted

In INNOVATE Mode (Ω₂)

Protected code boundaries are respected
Alternative approaches are proposed that work around protected sections

In PLAN Mode (Ω₃)

Work is planned around protected code
Permission is requested for modifying GUARDED code

In EXECUTE Mode (Ω₄)

PROTECTED and CRITICAL code remains untouched
GUARDED code only modified with explicit permission
Other protection levels handled according to guidelines

In REVIEW Mode (Ω₅)

Verifies all protection has been respected
Reports any violations
Documents any approved changes to GUARDED code



