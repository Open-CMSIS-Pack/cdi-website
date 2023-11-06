---
title: Open-CMSIS-CDI
description: >
  The Common Device Interface for IoT connected microcontrollers
layout: ../../layouts/Flow.astro
slug: ""
hero:
  title: Open-CMSIS-CDI
  description: >
    The Common Device Interface for IoT connected microcontrollers
  background_image: ../../assets/images/content/iot_planet_under_2mb.jpg

flow:
  - row: container_row
    sections:
      - component: title
        style: text-left font-weight-bold
        title_content:
          style: font-weight-bold
          size: h2
          text: Overview
      - component: text
        # style: text-center
        text_content:
          text: |-
            Open-CMSIS-CDI is a new project being proposed by Arm and Linaro to define a common device interface for microcontroller-based devices used in the Internet of Things (IoT).

            Today, developing and deploying IoT devices is hard. Developers used to building traditional embedded systems are suddenly faced with a huge range of complex requirements that must be met in order to support ever increasing use cases around connectivity, firmware update, machine learning and the need for long term support of devices that are deployed in the field. This is hindered further by a highly fragmented patchwork of standards and implementations. Software reuse and streamlined development processes common in other areas of software engineering, remain elusive to IoT developers.

            Particularly difficult problems include:

            1. Porting applications from one device to another – Every time you start a new project or move to a new device you take a step back. There is a raft of platform bring-up work you have to do just to get back to square one.

            2. Connecting to the Cloud services you want to use – Developers should be free to use the cloud services that are right for them, not be constrained to what is supported by their device.

            3. Managing and updating devices once they’re deployed in the field – Firmware update remains a difficult problem on most microcontroller platforms. Developers should not have to continually reimplement mechanisms for reflashing the firmware on their devices – this should be a basic property they can assume.

            4. Accessing and exploiting the potential of virtual hardware platforms – Virtual hardware is a powerful new technique of starting MCU-based development ahead of the availability of physical platforms. It also allows you to scale development and testing processes free of the cost and complexity of maintaining large physical board farms. Developers need better support to unlock the potential of virtual hardware.

            5. Security – Too often security is an afterthought, but the threats that a connected device faces evolve constantly. Having security built in from the start is essential to the integrity of IoT devices with long deployment lifecycles.

            The Open-CMSIS-CDI project will solve these problem by bringing together a set of established, best-in-class APIs to define a set of foundational device software interfaces which can be supported on every IoT connected microcontroller. We aren’t seeking to create something new from scratch – rather to bring together proven, established APIs and libraries to form a foundation that just works. We want to solve the problems which don’t differentiate one IoT device from another, allowing you to focus on the things which do differentiate your device.
  - row: container_row
    sections:
      - component: title
        style: text-left font-weight-bold
        title_content:
          style: font-weight-bold text-red
          size: h2
          text: "The first big problem: Secure Firmware Update"
      - component: text
        # style: text-center
        text_content:
          text: |-
            Through Open-CMSIS-CDI we want to build a complete device side software infrastructure. And the first problem we want to solve is this:
      - component: title
        style: text-center font-weight-bold px-3
        title_content:
          style: font-weight-bold
          size: h2
          text: Secure firmware update, for any IoT software stack running on microcontroller devices
      - component: text
        # style: text-center
        text_content:
          text: |-
            Building on top of standards such as [CMSIS](https://www.arm.com/technologies/cmsis), [PSA (The Platform Security Architecture)](https://www.arm.com/architecture/psa-certified) and [TrustedFirmware](https://www.trustedfirmware.org/), we want to ensure every microcontroller can handle firmware updates, irrespective of which device management service delivers them.
  - row: container_row
    sections:
      - component: title
        style: text-left font-weight-bold
        title_content:
          style: font-weight-bold
          size: h2
          text: Invitation To Participate
      - component: text
        # style: text-center
        text_content:
          text: |-
            Arm and Linaro are proposing to establish Open-CMSIS-CDI as a new community project, and a companion to the established [Open-CMSIS-Pack](https://www.open-cmsis-pack.org/) project. To learn more, we are inviting interested partners to join us for a first project call on **Thursday 21 April @ 15:00 UK time**.

            Further details of this call will be published sortly.

            If you are interested in joining and learning more about Open-CMSIS-CDI and our vision for a common microcontroller device interface, please contact Arm via [cmsis@arm.com](mailto:cmsis@arm.com).
  - row: container_row
    sections:
      - component: title
        style: text-left font-weight-bold
        title_content:
          style: font-weight-bold
          size: h2
          text: Resources
      - component: text
        style: #
        text_content:
          text: |-
            To learn more about Project Centauri, CMSIS and the Open-CMSIS-Pack project see:

            * Arm Project Centauri: [https://www.arm.com/solutions/iot/project-centauri](https://www.arm.com/solutions/iot/project-centauri)
            * CMSIS: [https://www.arm.com/technologies/cmsis](https://www.arm.com/technologies/cmsis)
            * Open-CMSIS-Pack: [https://www.open-cmsis-pack.org/](https://www.open-cmsis-pack.org/)
            * PSA - the Platform Security Architecture: [https://www.arm.com/architecture/psa-certified](https://www.arm.com/architecture/psa-certified)
            * TrustedFirmware: [https://www.trustedfirmware.org/](https://www.trustedfirmware.org/)
---
