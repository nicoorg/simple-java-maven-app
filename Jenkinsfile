@Library ('shared-library-nico@devel') _

log.info('este es mi mensaje')

properties(
    [parameters([choice(choices: ["A", "B", "C"].join("\n"),
    description: 'Some choice parameter',
    name: 'SOME_CHOICE')])])

node {
    stage  ('Example') {
        def mybranch = branchesInput()
        log.test('.')
        log.info ("El branch es ${mybranch}")
    }
}
