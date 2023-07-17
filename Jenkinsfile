#!/usr/bin/groovy
def productName = 'precip-notification-lambda'
def teamName = 'xplatform'

import static com.pelmorex.build.Platforms.PYTHON
import static com.pelmorex.build.DeploymentType.*

Map configuration = [
        platform                : PYTHON,
        team                    : teamName,
        product                 : productName,
        unitTests   : [
            enabled: true,
            junitReportPath: 'xunit-unit.xml',
            appDirectory: './app',
            command: './scripts/test.sh'
        ],
        codeAnalysis: [
            enabled: true,
        ]
]

pipe(configuration) { }
