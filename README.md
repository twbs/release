# Bootstrap Release Working Group

## Release schedule

| Release | Status          | Initial Release | Active LTS Start | Maintenance LTS Start | End-of-life |
| :-----: | :-------------: | :-------------: | :--------------: | :-------------------: | :---------: |
| [2.x][] | **End-of-life** | 2013-07-18      | -                | -                     | 2013-08-19  |
| [3.x][] | **End-of-life** | 2013-08-19      | 2014-11-01       | 2016-09-05            | 2019-07-24  |
| [4.x][] | **Active LTS**  | 2018-01-18      | 2019-11-26       | 2021-11-01            | 2023-01-01  |
| [5.x][] | **Active LTS**  | 2021-05-05      | TBD              | TBD                   | TBD         |

**Warning:** Dates may vary widely. We are actively working on strengthening timeline assurances.

[2.x]: https://getbootstrap.com/2.3.2/getting-started.html#download-bootstrap
[3.x]: https://getbootstrap.com/docs/3.4/getting-started/#download
[4.x]: https://getbootstrap.com/docs/4.5/getting-started/download/
[5.x]: https://getbootstrap.com/

## Release plan

New releases of Bootstrap are made from the `main` branch to the *Active* major version. At times to be determined by the release working group, major versions will be frozen and transitioned to *Long Term Support* (LTS). A long term support branch will be forked from `main`, making way for semver-major changes to be made on `main` and a new *Active* major version to be prepared.

A version in *Long Term Support* should not have new features landed without a compelling reason. It may continue to receive:

* Bug fixes
* Security updates
* Documentation updates

After a determined period of time, versions in Long Term Support will be deep-frozen and transition to *Maintenance*.

Versions in *Maintenance* should not have any changes landed, except for:

* **Critical** bug fixes
* **Critical** security updates
* **Important** documentation updates

Unless a change is urgent, *Maintenance* releases are likely to be made with minimal frequency.

## Upcoming release schedule

A rough schedule of releases has been included here for planning purposes.

### Bootstrap 4

- v4.5.3 in October 2020 (bug fixes and docs)
- v4.6.0 in January 2021 (feature alignment with v5 and docs)
- v4.6.1 in October 2021 (bug fixes and docs)
- v4.6.2 in July 2022 (bug fixes and docs)

### Bootstrap 5

- v5.0.0-alpha2 in September 2020 (delayed due to team vacations)
- v5.0.0-alpha3 in October 2020 (additional new features and breaking changes)
- v5.0.0-beta1 in December 2020 (final instance of breaking changes)
- v5.0.0-beta2 in January 2021 (beta features and bug fixes)
- v5.0.0-beta3 in March 2021 (beta bug fixes)
- v5.0.0 in May 2021 (stable release)
- v5.1.0 in August 2021
- v5.2.0 in July 2022 (beta in May 2022)
- v5.3.0 TBD

### Bootstrap 6

TBD.

## LTS team members

### Releasers

* [@mdo](https://github.com/mdo) – Mark Otto
* [@xhmikosr](https://github.com/xhmikosr)

### Security

* [@bardiharborow](https://github.com/bardiharborow) – Bardi Harborow
* [@Johann-S](https://github.com/Johann-S) – Johann Servoire
* [@xhmikosr](https://github.com/xhmikosr)
