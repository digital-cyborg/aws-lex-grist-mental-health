# aws-lex-grist-mental-health

## Inspiration

There are 1 in 4 people that suffer with mental health problems in the UK. Medical resources cannot deal with the increased number of people accessing medical services, partly due to several public campaigns that address the stigma around mental health problems. Increased demand have placed a strain on current medical resources. We aim to use technology to help provide tools for individuals and organisations to . We aim to help users self-assess their mental health, and if at risk, provide links to services for immediate support while they wait for the medical resources to become available. 

## What it does

An AWS Lex implementation of the GRiST mental health risk assessment system that allows users to self-assess their mental-health to determine whether they are at risk. If users are at risk we provide links to services for immediate support while waiting for the medical resources to become available. A further aim is to help filter the increasing demand on mental-health services and prioritise high-risk patients.

## How we built it

AWS Lex implementation that uses the API Gateway to access the GRiST Clinical Decision Support System (CDSS) to help determine individual risk of harm.

### GRiST

![GRiST Logo](https://github.com/digital-cyborg/aws-lex-grist-mental-health/blob/master/images/grist-logo-tiny.png) [GRiST](https://www.egrist.org/ "GRiST Website") uses a computational model of psychological processes to represent structured clinical judgements of multidisciplinary mental-health practitioners. GRiST models clinicians' expertise and how they perceive and assess mental health risk with the aim to assist with the early detection of mental-health risks. 

GRiST is being used by various NHS secondary Mental Health Trusts, charities, IAPT services. Recently, a version tailored to the needs of paramedics, A&E and other front line agencies was introduced to enable non-experts, such as 111 paramedics, to assess the initial risk of mental health patients in the same way that clinicians do. This allows high-risk patients to be directed to the right place for detailed monitoring. 


## Challenges we ran into


## Accomplishments that we're proud of

Creative video that highlights the problem space and how we are using technology to help

## What we learned

## What's next for Gaia Mental Health Risk Assessment

Further research on moving forward to clinical trials, with closer integration to NHS patient management systems.

An AWS Lex implementation of the GRiST mental health risk assessment system that allows users to self-assess their mental-health to determine whether they are at risk. If users are at risk we provide links to support services (e.g. PAPYRUS HOPELineUK) for immediate access. A futher aim is to help filter the increasing demand on mental-health services and prioritise high-risk patients.
