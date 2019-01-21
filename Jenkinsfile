@Library ('shared-library-nico@devel') _

log.info('este es mi mensaje')

properties([
    parameters([
        string(defaultValue: '/data', name: 'Directory'),
        , string(defaultValue: 'Dev', name: 'DEPLOY_ENV')
        ])
])

node {
    stage  ('Example') {
        def mybranch = branchesInput()
        log.test('.')
        log.info ("El branch es ${mybranch}")
    }
}
