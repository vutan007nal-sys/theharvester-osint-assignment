# theHarvester OSINT Assignment

## 1. Tool Name

theHarvester

## 2. Objective

The objective of this assignment is to understand passive
Open Source Intelligence (OSINT) and learn how to collect
publicly available information about an authorized domain.

## 3. Description

theHarvester is an OSINT reconnaissance tool used to gather
publicly available information from different search engines
and other data sources.

It can help identify information such as:

- Email addresses
- Subdomains
- Hostnames
- IP addresses
- URLs
- Publicly indexed information

## 4. Installation

TheHarvester was executed on Kali Linux.

Check installation:

    theHarvester --help

## 5. Command Used

Example:

    theHarvester -d example.com -l 100 -b duckduckgo

The target domain was used only for an authorized security
research/lab exercise.

## 6. Results

The tool was used to identify publicly available information
associated with the authorized domain.

### Information collected

- Email addresses: See screenshots/results
- Hosts/Subdomains: See screenshots/results
- URLs: See screenshots/results
- IP information: See screenshots/results

## 7. Advantages

- Easy to use
- Useful for passive reconnaissance
- Helps identify publicly available information
- Supports multiple data sources
- Useful during security assessments

## 8. Limitations

- Results depend on available public information
- Some sources may require API keys
- Search engines may limit requests
- Results can contain outdated information
- It should only be used against authorized targets

## 9. Screenshots

Screenshots are available in the `screenshots` directory.

## 10. Result Files

The command output is stored in:

    results/theHarvester-output.txt

## 11. Ethical Considerations

theHarvester should only be used for domains and systems
where the researcher has permission to perform reconnaissance.

Unauthorized reconnaissance may violate organizational
policies or applicable laws.

## 12. Conclusion

This assignment demonstrated how theHarvester can be used
for passive OSINT and reconnaissance. The exercise helped
understand how publicly available information can be collected
and analyzed during a security assessment.

## 13. References

- theHarvester GitHub repository
- Kali Linux documentation
- OSINT Framework
