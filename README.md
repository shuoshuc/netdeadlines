# :alarm_clock: Net Deadlines

Countdown timers to keep track of a bunch of networking conference deadlines.

## Current list of supported conferences:

**Networking:**

- ACM SIGCOMM:                          [https://conferences.sigcomm.org/sigcomm/2021/](https://conferences.sigcomm.org/sigcomm/2021/)
- USENIX NSDI:                              [https://www.usenix.org/conference/nsdi21](https://www.usenix.org/conference/nsdi21)
- ACM SOSR:                                  [https://conferences.sigcomm.org/sosr/2021/](https://conferences.sigcomm.org/sosr/2021/)
- ACM CoNEXT:                              [https://conferences.sigcomm.org/co-next/2021/](https://conferences.sigcomm.org/co-next/2021/)
- ACM IMC:                                      [https://conferences.sigcomm.org/imc/2021/](https://conferences.sigcomm.org/imc/2021/)
- USENIX ATC:                                [https://www.usenix.org/conference/atc21](https://www.usenix.org/conference/atc21)
- ACM HotNets (Workshop):         [https://conferences.sigcomm.org/hotnets/2021/](https://conferences.sigcomm.org/hotnets/2021/)
- P4 Workshop (Workshop): [https://opennetworking.org/2021-p4-workshop-content/](https://opennetworking.org/2021-p4-workshop-content/)
- EURO P4 (Workshop): [https://opennetworking.org/2021-p4-workshop-in-europe/](https://opennetworking.org/2021-p4-workshop-in-europe/)

**Network security:**

- USENIX SECURITY:                                 [https://www.usenix.org/conference/usenixsecurity21](https://www.usenix.org/conference/usenixsecurity21)
- NDSS Symposium (Internet Society):   [https://www.ndss-symposium.org/ndss2021/](https://www.ndss-symposium.org/ndss2021/)
- IEEE S&P:                                                  [https://www.ieee-security.org/TC/SP2021/](https://www.ieee-security.org/TC/SP2021/)
- ACM CCS:                                                 [https://www.sigsac.org/ccs/CCS2021/](https://www.sigsac.org/ccs/CCS2021/)
- ACM SIGCOMM SPIN (Workshop): [https://conferences.sigcomm.org/sigcomm/2021/workshop-spin.html](https://conferences.sigcomm.org/sigcomm/2021/workshop-spin.html)

**Privacy:**

- PETS: [https://petsymposium.org/](https://petsymposium.org/)

**Legacy:**
- <s>USENIX HotCloud (Workshop):  [https://www.usenix.org/conference/hotcloud20](https://www.usenix.org/conference/hotcloud20)</s> (suspended)
- <s>ACM SIGCOMM NetAI (Workshop): [https://conferences.sigcomm.org/sigcomm/2020/workshop-netai.html](https://conferences.sigcomm.org/sigcomm/2020/workshop-netai.html)</s> (discontinued)
- <s>USENIX HotSec (Summit):  [https://www.usenix.org/conference/hotsec20](https://www.usenix.org/conference/hotsec20)</s> (suspended)

## Contributing

Contributions are very welcome!

To add or update a deadline:
- Fork the repository
- Update `_data/conferences.yml`
- Make sure it has the `title`, `year`, `id`, `link`, `deadline`, `timezone`, `date`, `place`, `sub` attributes
    + See available timezone strings [here](https://momentjs.com/timezone/).
- Optionally add a `note` and `abstract_deadline` in case the conference has a separate mandatory abstract deadline
- Send a pull request


## License

Original design by: http://aideadlin.es/

[MIT](https://abhshkdz.mit-license.org/)
