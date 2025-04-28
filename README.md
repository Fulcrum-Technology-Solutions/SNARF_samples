# SNARF_samples

A collection of standardized cybersecurity documentation templates and examples for threat intelligence, detection engineering, incident response, and automated security operations.

Supports SNARF (Security Knowledge, Automation, and Response Framework).

## Repository Overview

This repository contains YAML templates and examples for standardizing cybersecurity documentation. The templates provide structured formats for documenting security threats, detection mechanisms, response procedures, automated playbooks, and testing methodologies.

## Repository Structure

```
SNARF_samples/
├── blueprints/                
│   ├── blueprint_sample.yaml       # Template for threat blueprints
│   └── BPT-00001.yaml # Example blueprint
│
├── detections/                
│   ├── detection_sample.yaml       # Template for detection rules
│   └── DET-00001.yaml # Example detection
│
├── response_runbooks/         
│   ├── response_runbook_sample.yaml       # Template for manual response procedures
│   └── RUN-00001.yaml # Example response runbook
│
├── soar_playbooks/            
│   ├── soar_playbook_sample.yaml       # Template for automated response playbooks
│   └── SOAR-00001.yaml # Example SOAR playbook
│
├── testing_runbooks/          
│   ├── testing_runbook_sample.yaml       # Template for validation procedures
│   └── TEST--00001.yaml # Example testing runbook
│
└── README.md                  # This file
```

## Template Descriptions

### Blueprints (`blueprints/`)

Threat blueprints document security threats or attack techniques in detail:
- Historical context and evolution
- Technical details of attack methods
- Organizational impact
- Current threat landscape
- Recommended defensive strategies

### Detections (`detections/`)

Detection documents define the logic and implementation for identifying threats:
- Detection methodology and approach
- Required data sources and logs
- Implementation guidance
- SIEM/EDR query logic
- False positive handling

### Response Runbooks (`response_runbooks/`)

Response runbooks provide step-by-step procedures for incident responders:
- Investigation methodologies
- Containment strategies
- Evidence collection requirements
- Decision matrices
- Documentation templates

### SOAR Playbooks (`soar_playbooks/`)

SOAR playbooks define automated response workflows:
- Integration requirements
- Automated action sequences
- Data enrichment procedures
- Notification workflows
- Documentation requirements

### Testing Runbooks (`testing_runbooks/`)

Testing runbooks offer procedures for validating detection and response capabilities:
- Test environment requirements
- Simulation procedures
- Validation criteria
- Performance benchmarks
- Troubleshooting guidance

## Using the Templates

1. Navigate to the appropriate directory for your documentation need
2. Use the corresponding `*_sample.yaml` file as your template
3. Reference the example files to see a completed version
4. Maintain the relationships between related documents (e.g., link detections to blueprints)

## Documentation Relationships

These templates form an interconnected documentation framework:

- Blueprints document threats that detections aim to identify
- Detections reference the blueprints they implement
- Response runbooks link to the detections that trigger them
- SOAR playbooks automate portions of response runbooks
- Testing runbooks validate detections and response procedures

## Best Practices

1. **Use Consistent Naming**: Follow the ID formats specified in templates
2. **Maintain Relationships**: Always link related documents properly
3. **Version Control**: Update version numbers when making significant changes
4. **Regular Review**: Set and follow review cycles for all documentation
5. **Test Implementation**: Validate that documented procedures work in practice