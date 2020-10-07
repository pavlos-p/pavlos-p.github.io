## Privacy-Preserving Passive DNS

**Abstract:** The Domain Name System (DNS) was created to resolve the IP addresses of web servers to easily remembered names. When it was initially created, security was not a major concern; nowadays, this lack of inherent security and trust has exposed the global DNS infrastructure to malicious actors. The passive DNS data collection process creates a database containing various DNS data elements, some of which are personal and need to be protected to preserve the privacy of the end users. To this end, we propose the use of distributed ledger technology. We use Hyperledger Fabric to create a permissioned blockchain, which only authorized entities can access. The proposed solution supports queries for storing and retrieving data from the blockchain ledger, allowing the use of the passive DNS database for further analysis, e.g., for the identification of malicious domain names. Additionally, it effectively protects the DNS personal data from unauthorized entities, including the administrators that can act as potential malicious insiders, and allows only the data owners to perform queries over these data. We evaluated our proposed solution by creating a proof-of-concept experimental setup that passively collects DNS data from a network and then uses the distributed ledger technology to store the data in an immutable ledger, thus providing a full historical overview of all the records.


<picture>
    <source type="images/webp" srcset="/images/PRESERVE_DNS_COVER.webp" />
    <source type="images/png" srcset="/images/PRESERVE_DNS_COVER.jpg" />
    <img class="z-depth-1" src="/images/PRESERVE_DNS_COVER.jpg" alt="Privacy-Preserving Passive DNS">
</picture>

<br><br>
MDPI Computers 2020, 9(3), 64; https://doi.org/10.3390/computers9030064

For more details: [Privacy-Preserving Passive DNS](https://www.mdpi.com/2073-431X/9/3/64).
